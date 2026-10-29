---
name: paper-unfold-mesh
description: Procedural paper that crumples, fans, folds or rolls and then opens frame by frame on a canvas — a 3D sheet mesh with crease fields, torn outlines and text/doodles printed on the paper so they deform with it, stepped at 6–12 fps. Use when a video needs paper-unfold reveals in many variations (different ball shapes, accordion, folded note, scroll, sticky notes) or writing that unfolds with the sheet; for the most photo-real single reveal prefer the paper-unfold-frames skill.
---

# Paper unfold from a procedural mesh

> **Status: working, with room for improvement.** The rolling loose ball, squashed sticky-note wads, accordion and scroll look good. The generated photo frames of the sister skill [`paper-unfold-frames`](https://github.com/OpenRootdev/paper-unfold-frames) still look more real. **Update this skill whenever a project gets better results**: new structures, better crumple geometry, fixes. Keep the "what went wrong" list current.

Full working source: `examples/paper-unfold-trials.html`, a single HyperFrames composition of 56 s with 9 scenes. It expects `assets/img/paper.jpg` (any paper texture), `assets/img/wood.jpg` (a top-down desk photo), the Caveat woff2 font and audio files you supply. The engine is plain canvas 2D plus GSAP for the clock, so it ports to Remotion or a web page.

## How it works

- **Sheet:** an (nx+1)×(ny+1) vertex grid in sheet units. The texture is a canvas the size of the sheet: paper colour, multiplied paper grain, then the content drawn by a `tex(g, w, h, k)` callback, where `k` is ink progress 0..1.
- **Crease field:** a sum of clamped V-tents `±min(|d|, wid)/wid` along random lines, normalised. This gives straight creases like real crumpled paper. Use few, wide tents for big folds and many, narrow ones for tight crinkles.
- **Kinds** (`pose(e)`, where e: 0 = closed and 1 = flat):
  - `ball`: a closed crumpled sphere `C` (sheet wrapped fully round, radius `s0·rmax/π`, radial crinkle noise plus tangential jitter). It blends into a cup whose edges meet *on top, facing the camera*, and the cup opens as its curvature κ→0. Per-vertex delays give uneven petals, outer paper first. Options: `squash` for flattened wads, `stagger`, `petals`, `crumple`, `ampBall`, `ampRes` (wrinkles left on the flat card).
  - `fan`: an accordion zig-zag that opens strip by strip. Use `ny: 1`: the strips are planes, and extra rows cause notches at the ridges.
  - `fold`: a quarter-folded note whose two flaps open in turn (b then a), recentred on its bounding box.
  - `scroll`: a spiral roll that unrolls left to right.
- **Torn outlines:** `torn: {base, rough, bites}` builds a ragged inset polygon (value noise plus bitten corners bridged by a jagged chord). The texture is masked with it and gets a 6 px white fibre stroke along the edge. Clamp each point inside its own inset, or the corners self-intersect into white slivers.
- **Render, per sheet per frame:** project (focal 3000, camera above the frame centre), sort facets back to front by mean z, then:
  1. **Paper pass:** clip to each facet grown on every edge (mitred offset 0.9 px, mitre capped), then affine-map the front texture or the back paper.
  2. **Shading:** fill and stroke the same facets into two opaque buffers, a darken buffer (white = none) and a lighten buffer (black = none). Mask both with the paper's alpha, then `multiply` and `screen` them onto the paper. Light comes from the upper left. Each facet's normal blends its face normal with averaged vertex normals (`smoothN` 0.6; use 0 for sharp folds: fan, fold).
  3. **Shadow:** every facet dropped onto the desk, offset by its height and blurred. For torn sheets, map the silhouette so the shadow follows the rip.
- **Clock:** each scene is quantised to its own fps (`floor(t·fps)`), with ±1.2 px / ±0.003 rad of seeded jitter per step. Release textures for sheets that are off screen.

## What went wrong (don't repeat)

- **Balls weren't closed or crumpled on frame 1:** a plain sphere wrap looks like a bag. Start from the closed crinkled sphere and blend out of it.
- **Closure facing away from the camera:** wrap so the edges gather on top.
- **See-through paper and a grid of lines:** the torn mask reused the last `fillStyle` (a 75% alpha colour). Always set `fillStyle = "#000"` and `globalAlpha = 1` before `destination-in`.
- **Square tiles:**
  - Quantising shading into brightness levels makes stair-stepped bands.
  - Drawing the shade as a second per-facet layer brightens anti-aliased edges.
  - Moving vertices out from the centroid leaves gaps along thin triangles.
  - The fixes are the separate shading buffers, edge-offset growth, a finer mesh (cells under about 20 px) and crinkle tents wider than about 3 cells.
- **Too slow:** unfolds of about 1–1.2 s feel right (a smoothstep over 1.2 s with a small 70 px spring-up), wads at 10 fps, and generally 8–12 fps.

## Ideas not yet tried

- Paper thickness (a 1–2 px edge colour on silhouettes).
- Self-shadowing in crease valleys (ambient occlusion from the crease field).
- Crumpling *into* a ball as an exit, with stronger tangential folding.
- A paper airplane or fortune-teller structure.
- Mapping a GPT-image paper photo as the texture, to combine both routes.
