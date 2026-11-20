# Portfolio d'Amal Bourahma

Site statique : une page `index.html` et un dossier `images/`. Aucune installation n'est nécessaire.

## Mise en ligne avec GitHub Pages

1. Créer un dépôt public nommé `IDENTIFIANT.github.io`, où IDENTIFIANT est votre identifiant GitHub.
2. Déposer à la racine du dépôt le contenu de ce dossier : `index.html`, `images/`, `.nojekyll` et ce fichier.
3. Dans le dépôt, ouvrir Settings, puis Pages. Choisir Deploy from a branch, la branche `main` et le dossier `/ (root)`.
4. Le site est en ligne après une ou deux minutes à l'adresse `https://IDENTIFIANT.github.io`.

En ligne de commande :

```bash
git init
git add .
git commit -m "Portfolio"
git branch -M main
git remote add origin https://github.com/IDENTIFIANT/IDENTIFIANT.github.io.git
git push -u origin main
```

## Modifier le site

Le texte se modifie directement dans `index.html`, entre les balises `<template id="tpl">` et `</template>`.
Les démonstrations interactives sont dans la classe `Component`, à la fin du fichier.

## Nom de domaine personnel (facultatif)

Acheter un domaine, par exemple chez OVH ou Gandi, puis le renseigner dans Settings, Pages, Custom domain, et suivre les instructions de GitHub pour la configuration DNS.
