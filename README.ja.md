<p align="center">
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/logo.svg" width="104" alt="Paper Unfold Mesh logo">
</p>

<h1 align="center">Paper Unfold Mesh</h1>

<p align="center">
  紙がくしゃっと丸まり、折りたたまれ、巻かれて、コマ送りで開きます。すべてコードで描画。<br>
  <sub>この表現を動画用に、無限のバリエーションで作れるよう AI エージェントに教えるスキルです。</sub>
</p>

<p align="center"><a href="https://github.com/Ker102/paper-unfold-mesh#readme">English</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.es.md">Español</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.de.md">Deutsch</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.fr.md">Français</a> · <b>日本語</b> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.zh-CN.md">简体中文</a> · <a href="https://github.com/Ker102/paper-unfold-mesh/blob/translations/README.pt-BR.md">Português</a></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/preview.gif" width="760" alt="木の机の上で、破れたグラフ、付箋2枚、じゃばら、巻物が開いていく様子">
</p>

<p align="center">
  <a href="https://github.com/Ker102/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip"><b>スキルをダウンロード</b></a> &nbsp;·&nbsp; <a href="#はじめかた">はじめかた</a> &nbsp;·&nbsp; <a href="https://github.com/Ker102/paper-unfold-mesh/blob/main/SKILL.md">スキルを読む</a>
</p>

<p align="center">
  <sub>対応</sub><br>
  <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/claude.svg" height="16" alt="">&nbsp;Claude Code &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/javascript.svg" height="16" alt="">&nbsp;JavaScript &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/Ker102/paper-unfold-mesh/assets/brands/gsap.svg" height="16" alt="">&nbsp;GSAP
</p>

<p align="center">
  <a href="https://toolindex.org/tools/paper-unfold-mesh/"><img src="https://toolindex.org/badges/paper-unfold-mesh.svg" alt="Listed in ToolIndex"></a>
</p>

## できること

エージェントが小さな三角形で紙を組み立て、ボール、じゃばら、折りたたんだメモ、巻物の形にしてから、手作り感のある毎秒 8〜12 コマで開いていきます。

- 毎回違う紙に：丸め方、破れた縁、色を調整できます。
- 文字や落書きは紙に印刷されるので、紙と一緒に曲がりしわになります。
- 画像モデル不要：ブラウザの canvas、HyperFrames、Remotion で動きます。

> [!NOTE]
> このスキルは改良中です。よりよいしわの付け方や新しい紙の形が見つかったら、ここで更新します。

## はじめかた

1. <code><a href="https://github.com/Ker102/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip">paper-unfold-mesh.zip</a></code> をダウンロードし、エージェントのスキルフォルダに展開します（Claude Code の場合は <code>~/.claude/skills/</code>）。
2. あとは普通の言葉でエージェントに頼むだけです。例：

   > *3つのステップを、じゃばら折りの紙が一折りずつ開いて見せるようにして。*

git でインストールする場合：

```bash
git clone --depth 1 https://github.com/Ker102/paper-unfold-mesh ~/.claude/skills/paper-unfold-mesh
```

## 必要なもの

- canvas に描画する、コードで作る動画（HyperFrames、Remotion、Web ページ）。
- 背景用の紙のテクスチャと机の写真（お好みで）。
- それ以外は不要：画像モデルも追加インストールもいりません。

## 中身

| | |
|---|---|
| [`SKILL.md`](https://github.com/Ker102/paper-unfold-mesh/blob/main/SKILL.md) | エージェントが従う手順書。失敗例と試したいアイデアも載っています。 |
| [`examples/paper-unfold-trials.html`](https://github.com/Ker102/paper-unfold-mesh/blob/main/examples/paper-unfold-trials.html) | 9シーンのデモ動画の全ソース。 |

<sub>プレビュー用の画像・動画は <a href="https://github.com/Ker102/paper-unfold-mesh/tree/assets"><code>assets</code></a> ブランチ、翻訳は <a href="https://github.com/Ker102/paper-unfold-mesh/tree/translations"><code>translations</code></a> ブランチにあり、<code>main</code> にはスキル本体だけが入っています。</sub>

## 姉妹スキル

<a href="https://github.com/Ker102/paper-unfold-frames"><img src="https://raw.githubusercontent.com/Ker102/paper-unfold-frames/assets/logo.svg" width="40" align="left" alt=""></a>
**[Paper Unfold Frames](https://github.com/Ker102/paper-unfold-frames)**<br>
写真のようにリアルな版：画像モデルが開く様子を描くので、本物の紙をコマ撮りしたように見えます。
<br clear="left">

---

<sub>MIT ライセンス · <a href="https://github.com/Ker102">Ker102</a></sub>
