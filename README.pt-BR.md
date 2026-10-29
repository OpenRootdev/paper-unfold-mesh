<p align="center">
  <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/logo.svg" width="104" alt="Paper Unfold Mesh logo">
</p>

<h1 align="center">Paper Unfold Mesh</h1>

<p align="center">
  Papel que amassa, dobra ou enrola e depois abre quadro a quadro. Desenhado inteiro em código.<br>
  <sub>Uma skill que ensina seu agente de IA a criar esse efeito para seus vídeos, com variações sem fim.</sub>
</p>

<p align="center"><a href="https://github.com/OpenRootdev/paper-unfold-mesh#readme">English</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.es.md">Español</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.de.md">Deutsch</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.fr.md">Français</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.ja.md">日本語</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.zh-CN.md">简体中文</a> · <b>Português</b></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/preview.gif" width="760" alt="Um gráfico rasgado, dois post-its, uma sanfona e um pergaminho se abrindo sobre uma mesa de madeira">
</p>

<p align="center">
  <a href="https://github.com/OpenRootdev/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip"><b>Baixar a skill</b></a> &nbsp;·&nbsp; <a href="#começar">Começar</a> &nbsp;·&nbsp; <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/main/SKILL.md">Ler a skill</a>
</p>

<p align="center">
  <sub>Funciona com</sub><br>
  <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/brands/claude.svg" height="16" alt="">&nbsp;Claude Code &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/brands/javascript.svg" height="16" alt="">&nbsp;JavaScript &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/brands/gsap.svg" height="16" alt="">&nbsp;GSAP
</p>

<p align="center">
  <a href="https://toolindex.org/tools/paper-unfold-mesh/"><img src="https://toolindex.org/badges/paper-unfold-mesh.svg" alt="Listed in ToolIndex"></a>
</p>

## O que faz

Seu agente monta uma folha com pequenos triângulos, amassa em bola, sanfona, bilhete dobrado ou pergaminho e abre de novo a 8–12 quadros por segundo, com cara de feito à mão.

- Cada folha é diferente: formato da bola, bordas rasgadas e cores são ajustáveis.
- Texto e rabiscos são impressos no papel, então dobram e amassam junto.
- Sem modelo de imagem: roda em qualquer canvas do navegador, HyperFrames ou Remotion.

> [!NOTE]
> Esta skill continua melhorando. Quando um projeto encontra um amassado melhor ou um novo formato de papel, a skill é atualizada aqui.

## Começar

1. Baixe <code><a href="https://github.com/OpenRootdev/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip">paper-unfold-mesh.zip</a></code> e descompacte na pasta de skills do seu agente (no Claude Code: <code>~/.claude/skills/</code>).
2. Depois é só pedir ao seu agente com palavras simples, por exemplo:

   > *Mostre nossos três passos em uma tira de papel sanfonada que se abre dobra por dobra.*

Ou instale com git:

```bash
git clone --depth 1 https://github.com/OpenRootdev/paper-unfold-mesh ~/.claude/skills/paper-unfold-mesh
```

## O que você precisa

- Um vídeo feito com código que desenha em um canvas (HyperFrames, Remotion ou uma página web).
- Uma textura de papel e uma foto de mesa para o fundo (as que quiser).
- Mais nada: sem modelo de imagem, sem instalações extras.

## O que vem dentro

- [`SKILL.md`](https://github.com/OpenRootdev/paper-unfold-mesh/blob/main/SKILL.md) · As instruções que seu agente segue, com o que deu errado e ideias para testar.
- [`examples/paper-unfold-trials.html`](https://github.com/OpenRootdev/paper-unfold-mesh/blob/main/examples/paper-unfold-trials.html) · O código completo do vídeo de demonstração com 9 cenas.

<sub>As mídias de prévia ficam no branch <a href="https://github.com/OpenRootdev/paper-unfold-mesh/tree/assets"><code>assets</code></a> e as traduções em <a href="https://github.com/OpenRootdev/paper-unfold-mesh/tree/translations"><code>translations</code></a>, então o <code>main</code> tem só a skill.</sub>

## Skill irmã

<a href="https://github.com/OpenRootdev/paper-unfold-frames"><img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-frames/assets/logo.svg" width="40" align="left" alt=""></a>
**[Paper Unfold Frames](https://github.com/OpenRootdev/paper-unfold-frames)**<br>
A versão fotorrealista: um modelo de imagem desenha a abertura, parecendo papel de verdade fotografado quadro a quadro.
<br clear="left">

---

<sub>Licença MIT · <a href="https://github.com/OpenRootdev">OpenRootdev</a></sub>
