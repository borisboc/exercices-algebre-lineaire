# exercices algèbre linéaire

Objectif : poser sur le papier des corrections d'exercices d'algèbre linéaire, pour me servir de référence

## Installation

Installez [uv](https://docs.astral.sh/uv/).

Pour build le livre (basé sur [Jupyter Book V1](https://jupyterbook.org/v1/intro.html)) : 

```
uv run jb build exercices_algebre_lineaire/
```

Le résultat doit être dans le dossier : `exercices_algebre_lineaire/_build/`

Vous pouvez ouvrir la page d'accueil : `exercices_algebre_lineaire/_build/html/intro.html`

Pour pouvoir exécuter (et modifier) les notebooks, lancez un serveur jupyter notebook : 

```
uv run jupyter notebook
```


## Pourquoi Jupyter Book V1 ?

Certes, il existe la version V2. Mais j'apprécie la version 1, car le résultat du build est un siteweb static, ne nécessitant pas un serveur web. Ce qui simplifie l'échange du livre.