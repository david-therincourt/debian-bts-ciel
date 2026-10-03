---
title: Markdown
nav_order: 7
permalink: /markdown/
layout: post
---

## MarkText

**MarkText** est un éditeur Markdown libre, avec un rendu en direct pendant la saisie :
le texte est mis en forme au fur et à mesure (titres, listes, tableaux, code, formules
mathématiques, diagrammes). Il exporte en HTML et en PDF.

### Option 1 : Flatpak

MarkText s'installe depuis Flathub (voir [Flatpak et Flathub]({{ '/systeme/#flatpak-et-flathub' | relative_url }})) :

```bash
flatpak install flathub com.github.marktext.marktext
```

### Option 2 : paquet `.deb` depuis GitHub

Téléchargez le fichier `marktext-linux-<version>.deb` sur la page
[des versions de MarkText](https://github.com/marktext/marktext/releases/latest),
puis installez-le avec `apt`, qui récupère aussi les dépendances :

```bash
cd ~/Téléchargements
sudo apt install ./marktext-linux-*.deb
```

> ##### Remarque
>
> Le `./` devant le nom du fichier est indispensable : il indique à `apt` d'installer
> un fichier local plutôt qu'un paquet des dépôts.
{: .block-tip }

> ##### Attention
>
> Un paquet `.deb` installé à la main n'est pas mis à jour automatiquement.
> Pour passer à une nouvelle version, téléchargez le nouveau fichier et relancez la même commande.
{: .block-warning }
