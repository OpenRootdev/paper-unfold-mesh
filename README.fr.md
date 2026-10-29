<p align="center">
  <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/logo.svg" width="104" alt="Paper Unfold Mesh logo">
</p>

<h1 align="center">Paper Unfold Mesh</h1>

<p align="center">
  Du papier qui se froisse, se plie ou s'enroule, puis s'ouvre image par image. Entièrement dessiné en code.<br>
  <sub>Un skill qui apprend à votre agent IA à créer cet effet pour vos vidéos, en variations infinies.</sub>
</p>

<p align="center"><a href="https://github.com/OpenRootdev/paper-unfold-mesh#readme">English</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.es.md">Español</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.de.md">Deutsch</a> · <b>Français</b> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.ja.md">日本語</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.zh-CN.md">简体中文</a> · <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/translations/README.pt-BR.md">Português</a></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/preview.gif" width="760" alt="Un graphique déchiré, deux notes adhésives, un accordéon et un rouleau qui se déplient sur un bureau en bois">
</p>

<p align="center">
  <a href="https://github.com/OpenRootdev/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip"><b>Télécharger le skill</b></a> &nbsp;·&nbsp; <a href="#démarrer">Démarrer</a> &nbsp;·&nbsp; <a href="https://github.com/OpenRootdev/paper-unfold-mesh/blob/main/SKILL.md">Lire le skill</a>
</p>

<p align="center">
  <sub>Fonctionne avec</sub><br>
  <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/brands/claude.svg" height="16" alt="">&nbsp;Claude Code &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/brands/javascript.svg" height="16" alt="">&nbsp;JavaScript &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-mesh/assets/brands/gsap.svg" height="16" alt="">&nbsp;GSAP
</p>

<p align="center">
  <a href="https://toolindex.org/tools/paper-unfold-mesh/"><img src="https://toolindex.org/badges/paper-unfold-mesh.svg" alt="Listed in ToolIndex"></a>
</p>

## Ce que ça fait

Votre agent construit une feuille à partir de petits triangles, la froisse en boule, en accordéon, en note pliée ou en rouleau, puis la rouvre à 8–12 images par seconde, comme fait main.

- Chaque feuille est différente : forme de la boule, bords déchirés et couleurs réglables.
- Le texte et les dessins sont imprimés sur le papier : ils se plient avec lui.
- Aucun modèle d'images : fonctionne dans tout canvas de navigateur, HyperFrames ou Remotion.

> [!NOTE]
> Ce skill continue de s'améliorer. Quand un projet trouve un meilleur froissé ou une nouvelle forme, le skill est mis à jour ici.

## Démarrer

1. Téléchargez <code><a href="https://github.com/OpenRootdev/paper-unfold-mesh/releases/latest/download/paper-unfold-mesh.zip">paper-unfold-mesh.zip</a></code> et décompressez-le dans le dossier de skills de votre agent (pour Claude Code : <code>~/.claude/skills/</code>).
2. Demandez-le simplement à votre agent, par exemple :

   > *Montre nos trois étapes sur une bande de papier en accordéon qui se déplie pli par pli.*

Ou installez-le avec git :

```bash
git clone --depth 1 https://github.com/OpenRootdev/paper-unfold-mesh ~/.claude/skills/paper-unfold-mesh
```

## Ce qu'il vous faut

- Une vidéo faite en code qui dessine sur un canvas (HyperFrames, Remotion ou une page web).
- Une texture de papier et une photo de bureau pour le fond (au choix).
- Rien d'autre : ni modèle d'images, ni installation supplémentaire.

## Contenu

- [`SKILL.md`](https://github.com/OpenRootdev/paper-unfold-mesh/blob/main/SKILL.md) · Les instructions que suit votre agent, avec ce qui a raté et des idées à essayer.
- [`examples/paper-unfold-trials.html`](https://github.com/OpenRootdev/paper-unfold-mesh/blob/main/examples/paper-unfold-trials.html) · Le code complet de la vidéo de démo en 9 scènes.

<sub>Les médias d'aperçu sont sur la branche <a href="https://github.com/OpenRootdev/paper-unfold-mesh/tree/assets"><code>assets</code></a> et les traductions sur <a href="https://github.com/OpenRootdev/paper-unfold-mesh/tree/translations"><code>translations</code></a> : <code>main</code> ne contient que le skill.</sub>

## Skill jumeau

<a href="https://github.com/OpenRootdev/paper-unfold-frames"><img src="https://raw.githubusercontent.com/OpenRootdev/paper-unfold-frames/assets/logo.svg" width="40" align="left" alt=""></a>
**[Paper Unfold Frames](https://github.com/OpenRootdev/paper-unfold-frames)**<br>
La version photoréaliste : un modèle d'images dessine le dépliage, comme du vrai papier photographié image par image.
<br clear="left">

---

<sub>Licence MIT · <a href="https://github.com/OpenRootdev">OpenRootdev</a></sub>
