<p align="center">
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/logo.svg" width="104" alt="Paper Unfold Mesh logo">
</p>

<h1 align="center">Paper Unfold Mesh</h1>

<p align="center">
  Papier, das sich zerknüllt, faltet oder aufrollt und dann Bild für Bild öffnet. Komplett in Code gezeichnet.<br>
  <sub>Ein Skill, der deinem KI-Agenten beibringt, diesen Effekt für deine Videos zu erstellen, in endlosen Varianten.</sub>
</p>

<p align="center"><a href="https://github.com/Ker102/paper-unfold-mesh#readme">English</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.es.md">Español</a> · <b>Deutsch</b> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.fr.md">Français</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.ja.md">日本語</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.zh-CN.md">简体中文</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.pt-BR.md">Português</a></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/preview.gif" width="760" alt="Ein eingerissenes Diagramm, zwei Haftnotizen, ein Akkordeon und eine Rolle entfalten sich auf einem Holztisch">
</p>

<p align="center">
  <a href="https://github.com/Ker102/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip"><b>Skill herunterladen</b></a> &nbsp;·&nbsp; <a href="#loslegen">Loslegen</a> &nbsp;·&nbsp; <a href="https://github.com/Ker102/paper-unfold-mesh/blob/main/SKILL.md">Skill lesen</a>
</p>

<p align="center">
  <sub>Funktioniert mit</sub><br>
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/claude.svg" height="16" alt="">&nbsp;Claude Code &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/javascript.svg" height="16" alt="">&nbsp;JavaScript &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/gsap.svg" height="16" alt="">&nbsp;GSAP
</p>

<p align="center">
  <a href="https://toolindex.org/tools/paper-unfold-mesh/"><img src="https://toolindex.org/badges/paper-unfold-mesh.svg" alt="Listed in ToolIndex"></a>
</p>

## Was es macht

Dein Agent baut ein Blatt aus kleinen Dreiecken, knüllt es zu einer Kugel, einem Akkordeon, einem gefalteten Zettel oder einer Rolle und öffnet es wieder, mit handgemachten 8–12 Bildern pro Sekunde.

- Jedes Blatt ist anders: Kugelform, Risskanten und Farben sind einstellbar.
- Text und Kritzeleien sind aufs Papier gedruckt und knicken mit.
- Kein Bildmodell nötig: läuft in jedem Browser-Canvas, in HyperFrames oder Remotion.

> [!NOTE]
> Dieser Skill wird laufend besser. Wenn ein Projekt eine bessere Knitterung oder eine neue Papierform findet, wird der Skill hier aktualisiert.

## Loslegen

1. Lade <code><a href="https://github.com/Ker102/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip">paper-unfold-mesh.zip</a></code> herunter und entpacke es in den Skills-Ordner deines Agenten (bei Claude Code: <code>~/.claude/skills/</code>).
2. Bitte deinen Agenten in ganz normalen Worten darum, zum Beispiel:

   > *Zeig unsere drei Schritte auf einem Akkordeon-Papierstreifen, der sich Falte für Falte öffnet.*

Oder mit git installieren:

```bash
git clone --depth 1 https://github.com/Ker102/paper-unfold-mesh ~/.claude/skills/paper-unfold-mesh
```

## Was du brauchst

- Ein Video aus Code, das auf ein Canvas zeichnet (HyperFrames, Remotion oder eine Webseite).
- Eine Papiertextur und ein Foto eines Tisches als Hintergrund (beliebig).
- Sonst nichts: kein Bildmodell, keine weiteren Installationen.

## Was drin ist

| | |
|---|---|
| [`SKILL.md`](https://github.com/Ker102/paper-unfold-mesh/blob/main/SKILL.md) | Die Anleitung für deinen Agenten, inklusive Fehlern und Ideen zum Ausprobieren. |
| [`examples/paper-unfold-trials.html`](https://github.com/Ker102/paper-unfold-mesh/blob/main/examples/paper-unfold-trials.html) | Der komplette Quellcode des Demo-Videos mit 9 Szenen. |

<sub>Vorschau-Medien liegen im Branch <a href="https://github.com/Ker102/paper-unfold-mesh/tree/assets"><code>assets</code></a>, Übersetzungen in <a href="https://github.com/Ker102/paper-unfold-mesh/tree/translations"><code>translations</code></a> – <code>main</code> enthält nur den Skill.</sub>

## Schwester-Skill

<a href="https://github.com/Ker102/paper-unfold-frames"><img src="https://raw.githubusercontent.com/Ker102/paper-unfold-frames/assets/logo.svg" width="40" align="left" alt=""></a>
**[Paper Unfold Frames](https://github.com/Ker102/paper-unfold-frames)**<br>
Die fotorealistische Version: Ein Bildmodell zeichnet das Entfalten, es sieht aus wie echtes Papier, Bild für Bild fotografiert.
<br clear="left">

---

<sub>MIT-Lizenz · <a href="https://github.com/Ker102">Ker102</a></sub>
