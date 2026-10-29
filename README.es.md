<p align="center">
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/logo.svg" width="104" alt="Paper Unfold Mesh logo">
</p>

<h1 align="center">Paper Unfold Mesh</h1>

<p align="center">
  Papel que se arruga, se pliega o se enrolla y luego se abre fotograma a fotograma. Todo dibujado con código.<br>
  <sub>Una skill que enseña a tu agente de IA a crear este efecto para tus vídeos, con variaciones infinitas.</sub>
</p>

<p align="center"><a href="https://github.com/Ker102/paper-unfold-mesh#readme">English</a> · <b>Español</b> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.de.md">Deutsch</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.fr.md">Français</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.ja.md">日本語</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.zh-CN.md">简体中文</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.pt-BR.md">Português</a></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/preview.gif" width="760" alt="Un gráfico rasgado, dos notas adhesivas, un acordeón y un pergamino desplegándose sobre una mesa de madera">
</p>

<p align="center">
  <a href="https://github.com/Ker102/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip"><b>Descargar la skill</b></a> &nbsp;·&nbsp; <a href="#primeros-pasos">Primeros pasos</a> &nbsp;·&nbsp; <a href="https://github.com/Ker102/paper-unfold-mesh/blob/main/SKILL.md">Leer la skill</a>
</p>

<p align="center">
  <sub>Funciona con</sub><br>
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/claude.svg" height="16" alt="">&nbsp;Claude Code &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/javascript.svg" height="16" alt="">&nbsp;JavaScript &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/gsap.svg" height="16" alt="">&nbsp;GSAP
</p>

<p align="center">
  <a href="https://toolindex.org/tools/paper-unfold-mesh/"><img src="https://toolindex.org/badges/paper-unfold-mesh.svg" alt="Listed in ToolIndex"></a>
</p>

## Qué hace

Tu agente construye una hoja de papel con pequeños triángulos, la arruga en una bola, un acordeón, una nota doblada o un pergamino, y la vuelve a abrir a 8–12 fotogramas por segundo, como hecho a mano.

- Cada hoja es distinta: forma de la bola, bordes rasgados y colores, todo ajustable.
- El texto y los dibujos están impresos en el papel, así que se doblan y arrugan con él.
- No necesita modelo de imágenes: funciona en cualquier canvas del navegador, HyperFrames o Remotion.

> [!NOTE]
> Esta skill sigue mejorando. Cuando un proyecto consigue un arrugado mejor o una forma nueva, la skill se actualiza aquí.

## Primeros pasos

1. Descarga <code><a href="https://github.com/Ker102/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip">paper-unfold-mesh.zip</a></code> y descomprímelo en la carpeta de skills de tu agente (en Claude Code: <code>~/.claude/skills/</code>).
2. Pídeselo a tu agente con palabras normales, por ejemplo:

   > *Muestra nuestros tres pasos en una tira de papel en acordeón que se despliega pliegue a pliegue.*

O instálala con git:

```bash
git clone --depth 1 https://github.com/Ker102/paper-unfold-mesh ~/.claude/skills/paper-unfold-mesh
```

## Qué necesitas

- Un vídeo hecho con código que dibuje en un canvas (HyperFrames, Remotion o una página web).
- Una textura de papel y una foto de una mesa para el fondo (las que quieras).
- Nada más: sin modelo de imágenes ni instalaciones extra.

## Qué incluye

- [`SKILL.md`](https://github.com/Ker102/paper-unfold-mesh/blob/main/SKILL.md) · Las instrucciones que sigue tu agente, con lo que salió mal e ideas por probar.
- [`examples/paper-unfold-trials.html`](https://github.com/Ker102/paper-unfold-mesh/blob/main/examples/paper-unfold-trials.html) · El código completo del vídeo de demostración de 9 escenas.

<sub>Los vídeos e imágenes de muestra están en la rama <a href="https://github.com/Ker102/paper-unfold-mesh/tree/assets"><code>assets</code></a> y las traducciones en <a href="https://github.com/Ker102/paper-unfold-mesh/tree/translations"><code>translations</code></a>, así <code>main</code> contiene solo la skill.</sub>

## Skill hermana

<a href="https://github.com/Ker102/paper-unfold-frames"><img src="https://raw.githubusercontent.com/Ker102/paper-unfold-frames/assets/logo.svg" width="40" align="left" alt=""></a>
**[Paper Unfold Frames](https://github.com/Ker102/paper-unfold-frames)**<br>
La versión fotorrealista: un modelo de imágenes dibuja el despliegue, así que parece papel real fotografiado fotograma a fotograma.
<br clear="left">

---

<sub>Licencia MIT · <a href="https://github.com/Ker102">Ker102</a></sub>
