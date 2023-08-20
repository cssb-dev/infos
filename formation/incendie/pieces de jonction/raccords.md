---
layout: post
title: Raccords
rank: 6
---

## Raccords

Constitués de demi-raccords, ils servent à brancher 2 tuyaux, 1 tuyaux et une prise d’eau etc.. entre eux. Il en existe donc plusieurs types:

-  **Les demi-raccords :** ils servent essentiellement à raccorder deux tuyaux entre eux:

![Alt text](image.png)

-   **Raccords intermédiaires et de réduction :** ce sont des pièces de jonction comportant deux raccords d’un modèle différent, montées sur
un même corps. 

![Alt text](image-1.png)

## Quelques infos

Début d'un nouveau paragraphe, sans indentation.
Toute ligne rajouté dans le markdown sans espace après continue ce paragraphe.

En laissant une autre ligne dans le markdown, on commence un nouveau paragraphe.
Par défault, tout les paragraphes commencent sans alinéa (indentation). Il y a deux manière de modifier ça :

1. ajouter globalement un alinéa au début de chaque paragraphe, en modifiant les attributs css de paragraphe, voir le fichier `_scss/_typography.scss`, en particulier la partie ici :
```scss
// Paragraphs
p {
  margin: 0 0 $line-height / 2;
  opacity: 0.8;
  font-weight: 600;
  // text-indent: 2em;
}
```
$\Rightarrow$ décommenter la partie avec `text-indent` permet d'ajouter à chaque paragraphe un alinéa avec une longeur donnée (ici `2em`, peut aussi être donnée en pixels, par ex. `10px`).

2. rajouter localement des espaces au début de chaque paragraphe. Par example, avec le symbole `&nbsp;` (espace en html), et en le mettant avant de début de chaque paragraphe :

```markdown
Le premier paragraphe, lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

&nbsp;&nbsp;&nbsp;&nbsp;
Le deuxième paragraphe, lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
```
Ce qui donne :

---
Le premier paragraphe, lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

&nbsp;&nbsp;&nbsp;&nbsp;
Le deuxième paragraphe, lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

---

Il est aussi possible de le faire localement avec du [LaTex](https://www.overleaf.com/learn) :

```markdown
Le premier paragraphe, lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

$\hspace{10pt}$
Le deuxième paragraphe, lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
```
ce qui donne :

---

Le premier paragraphe, lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

$\hspace{10pt}$
Le deuxième paragraphe, lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

---