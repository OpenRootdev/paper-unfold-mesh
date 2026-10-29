<p align="center">
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/logo.svg" width="104" alt="Paper Unfold Mesh logo">
</p>

<h1 align="center">Paper Unfold Mesh</h1>

<p align="center">
  纸张揉皱、折叠或卷起，然后逐帧展开。完全用代码绘制。<br>
  <sub>一个教你的 AI 智能体为视频制作这种效果的技能，变化无穷。</sub>
</p>

<p align="center"><a href="https://github.com/Ker102/paper-unfold-mesh#readme">English</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.es.md">Español</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.de.md">Deutsch</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.fr.md">Français</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.ja.md">日本語</a> · <b>简体中文</b> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.pt-BR.md">Português</a></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/preview.gif" width="760" alt="木桌上一张撕边图表、两张便利贴、一条风琴折纸和一个卷轴依次展开">
</p>

<p align="center">
  <a href="https://github.com/Ker102/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip"><b>下载技能</b></a> &nbsp;·&nbsp; <a href="#快速开始">快速开始</a> &nbsp;·&nbsp; <a href="https://github.com/Ker102/paper-unfold-mesh/blob/main/SKILL.md">阅读技能</a>
</p>

<p align="center">
  <sub>适用于</sub><br>
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/claude.svg" height="16" alt="">&nbsp;Claude Code &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/javascript.svg" height="16" alt="">&nbsp;JavaScript &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/gsap.svg" height="16" alt="">&nbsp;GSAP
</p>

<p align="center">
  <a href="https://toolindex.org/tools/paper-unfold-mesh/"><img src="https://toolindex.org/badges/paper-unfold-mesh.svg" alt="Listed in ToolIndex"></a>
</p>

## 它能做什么

智能体用许多小三角形搭出一张纸，把它揉成纸团、折成风琴、叠成便条或卷成卷轴，再以每秒 8–12 帧的手工感重新展开。

- 每张纸都不一样：纸团形状、撕边和颜色都可调。
- 文字和涂鸦印在纸上，会随纸一起弯折起皱。
- 无需图像模型：可在任何浏览器 canvas、HyperFrames 或 Remotion 中运行。

> [!NOTE]
> 这个技能仍在改进。当某个项目找到更好的揉皱方式或新的纸张形状时，会在这里更新。

## 快速开始

1. 下载 <code><a href="https://github.com/Ker102/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip">paper-unfold-mesh.zip</a></code>，解压到你的智能体的技能文件夹（Claude Code 为 <code>~/.claude/skills/</code>）。
2. 然后用平常的话告诉你的智能体，例如：

   > *用一条风琴折的纸条一折一折展开，展示我们的三个步骤。*

或者用 git 安装：

```bash
git clone --depth 1 https://github.com/Ker102/paper-unfold-mesh ~/.claude/skills/paper-unfold-mesh
```

## 你需要什么

- 一个在 canvas 上绘制的代码视频（HyperFrames、Remotion 或网页）。
- 一张纸张纹理和一张桌面照片作为背景（任选）。
- 别的都不需要：没有图像模型，也不用额外安装。

## 包含内容

- [`SKILL.md`](https://github.com/Ker102/paper-unfold-mesh/blob/main/SKILL.md) · 智能体遵循的说明，包括踩过的坑和待尝试的想法。
- [`examples/paper-unfold-trials.html`](https://github.com/Ker102/paper-unfold-mesh/blob/main/examples/paper-unfold-trials.html) · 9 个场景演示视频的完整源码。

<sub>预览图片和视频放在 <a href="https://github.com/Ker102/paper-unfold-mesh/tree/assets"><code>assets</code></a> 分支，翻译放在 <a href="https://github.com/Ker102/paper-unfold-mesh/tree/translations"><code>translations</code></a> 分支，<code>main</code> 只包含技能本身。</sub>

## 姊妹技能

<a href="https://github.com/Ker102/paper-unfold-frames"><img src="https://raw.githubusercontent.com/Ker102/paper-unfold-frames/assets/logo.svg" width="40" align="left" alt=""></a>
**[Paper Unfold Frames](https://github.com/Ker102/paper-unfold-frames)**<br>
照片级真实的版本：由图像模型画出展开过程，看起来像逐帧拍摄的真纸。
<br clear="left">

---

<sub>MIT 许可证 · <a href="https://github.com/Ker102">Ker102</a></sub>
