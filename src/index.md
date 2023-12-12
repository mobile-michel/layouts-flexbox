---
title: Flexbox
description: Flexbox layouts with Sass processing.
layout: base
---
## Qu'est-ce que Flexbox

Flexbox, ou Flexible Box Layout, est un modèle de mise en page CSS qui permet de créer des interfaces utilisateur flexibles et réactives. Il permet de contrôler la direction, l'alignement, la taille et l'ordre des éléments, même lorsque leur taille est inconnue ou dynamique.

Voici un exemple de base de l'utilisation de Flexbox :

.container {
  display: flex;
  justify-content: space-between;
}

.item {
  flex-grow: 1;
}

Dans cet exemple, .container est un conteneur flex, et tous ses enfants directs deviennent des éléments flex. justify-content: space-between; aligne les éléments flex de manière à ce qu'il y ait un espace égal entre eux. flex-grow: 1; permet à chaque élément flex de grandir pour occuper tout l'espace disponible dans le conteneur.