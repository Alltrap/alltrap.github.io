---
title: "Création d'une interface en C#"
date: 2024-11-14
draft: false
github_link: "https://github.com/gurusabarish/hugo-profile"
author: "NOIROT Lucas"
tags:
  - AP
  - HUGO
  - Portfolio
image: /images/JavaScript.png
description: ""
toc: 
---
## Présentation du projet

Afin d'étudier le javascript nous avons créer un cliker à partir d'une base deja existante, on nous a demander de coder le jeu afin en suivent ces principes :

- il faut cliquer sur une image.
- à chaque clic le score augmente de 1.
- pour arriver au niveau 1, il faut 15 clics, puis pour chaque niveau suivant on multiplie par 2 le nombre de clics nécessaires au niveau précédent (niveau 1 : 15 clics, niveau 2 : 30 clics, niveau 3 : 60 clics, niveau 4 : 120 clics, …).
- a chaque fois que l’on arrive au niveau supérieur, le nombre de clics actuel devient le nombre de clics auquel on retire le nombre de clics utilisés pour passer au niveau supérieur.
- On veut que les joueurs puissent se connecter avec leur nom / mot de passe grâce à un formulaire de connexion.
- Lorsqu’un joueur se connecte, le jeu s’initialise avec le nombre de clics et le niveau qui correspondent à son compte dans la base de données.
## Résultat Obtenu
<center>
<img src="/images/ap-clics.png">
</center>
<!-- The [emojify](https://gohugo.io/functions/emojify/) function can be called directly in templates or [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes).

To enable emoji globally, set ```enableEmoji``` to ```true``` in your site’s [configuration](https://gohugo.io/getting-started/configuration/) and then you can type emoji shorthand codes directly in content files; e.g.

The [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/) is a useful reference for emoji shorthand codes.

<hr>

**N.B.** The above steps enable Unicode Standard emoji characters and sequences in Hugo, however the rendering of these glyphs depends on the browser and the platform. To style the emoji you can either use a third party emoji font or a font stack; e.g.-->


