<p align="center">
  <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/logo.svg" width="104" alt="Paper Unfold Mesh logo">
</p>

<h1 align="center">Paper Unfold Mesh</h1>

<p align="center">
  Paper that crumples, folds or rolls up, then opens frame by frame. Drawn entirely in code.<br>
  <sub>A skill that teaches your AI agent to make this effect for your videos, in endless variations.</sub>
</p>

<p align="center"><b>English</b> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.es.md">Español</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.de.md">Deutsch</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.fr.md">Français</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.ja.md">日本語</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.zh-CN.md">简体中文</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.pt-BR.md">Português</a></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/preview.gif" width="760" alt="A torn chart, two sticky notes, an accordion and a scroll unfolding on a wooden desk">
</p>

<p align="center">
  <a href="https://github.com/OpenRootdev/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip"><b>Download the skill</b></a> &nbsp;·&nbsp; <a href="#get-started">Get started</a> &nbsp;·&nbsp; <a href="SKILL.md">Read the skill</a>
</p>

<p align="center">
  <sub>Works with</sub><br>
  <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/brands/claude.svg" height="16" alt="">&nbsp;Claude Code &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/brands/javascript.svg" height="16" alt="">&nbsp;JavaScript &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/brands/gsap.svg" height="16" alt="">&nbsp;GSAP
</p>

<p align="center">
  <a href="https://toolindex.org/tools/paper-unfold-mesh/"><img src="https://toolindex.org/badges/paper-unfold-mesh.svg" alt="Listed in ToolIndex"></a>
</p>

## What it does

Your agent builds a sheet of paper from small triangles, crumples it into a ball, an accordion, a folded note or a scroll, and opens it again at a hand-made 8–12 frames per second.

- Every sheet is different: ball shapes, torn edges and colours are all adjustable.
- Text and doodles are printed on the paper, so they bend and crease with it.
- No image model needed: it runs in any browser canvas, HyperFrames or Remotion.

> [!NOTE]
> This skill is still improving. When a project finds a better crumple or a new paper shape, the skill gets updated here.

## Get started

1. Download <code><a href="https://github.com/OpenRootdev/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip">paper-unfold-mesh.zip</a></code> and unzip it into your agent's skills folder (for Claude Code: <code>~/.claude/skills/</code>).
2. Ask your agent for it in plain words, for example:

   > *Show our three steps on an accordion strip of paper that unfolds one fold at a time.*

Or install with git:

```bash
git clone --depth 1 https://github.com/OpenRootdev/paper-unfold-mesh ~/.claude/skills/paper-unfold-mesh
```

## What you need

- A video made from code that draws on a canvas (HyperFrames, Remotion or a web page).
- A paper texture and a desk photo for the background (any you like).
- Nothing else: no image model, no extra installs.

## What's inside

- [`SKILL.md`](SKILL.md) · The instructions your agent follows, including what went wrong and ideas to try.
- [`examples/paper-unfold-trials.html`](examples/paper-unfold-trials.html) · The full source of the 9-scene demo reel.

<sub>Preview media lives on the <a href="https://github.com/OpenRootdev/paper-unfold-mesh/tree/assets"><code>assets</code></a> branch and translations on <a href="https://github.com/OpenRootdev/paper-unfold-mesh/tree/translations"><code>translations</code></a>, so <code>main</code> holds only the skill.</sub>

## Sister skill

<a href="https://github.com/OpenRootdev/paper-unfold-frames"><img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-frames/assets/logo.svg" width="40" align="left" alt=""></a>
**[Paper Unfold Frames](https://github.com/OpenRootdev/paper-unfold-frames)**<br>
The photo-real version: an image model draws the unfold, so it looks like real paper photographed frame by frame.
<br clear="left">

---

<sub>MIT licence · <a href="https://github.com/OpenRootdev">OpenRootdev</a></sub>
