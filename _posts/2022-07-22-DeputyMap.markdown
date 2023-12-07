---
title: DéputéMap, a map to understand how Members of Parlament relate to each other. 
layout: post
date: 2022-07-22 12:00
tag: DataViz, WebDev, Python, API
image: /assets/images/assnat.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: ""
category: project
author: Thomas Benchetrit
externalLink: false
---

This is a project carried out for fun
Made alone
---
Problématique/Research questions
Qu'est ce que j'ai fait 
Donnée prises des votes des députées pendant la 15eme legislature 
En gros j'ai pris tout les votes de chacuns des députée pendant la 15eme legislatures, puis à l'aide de ses votes (si les députés ont voté pour, contre, ou abstention), j'ai crée un embedding des députés.
A partir de cet embedding en N dimensions, N étant le nombre de votes, j'ai fais de la dimensiolatiy reduction pour obtenir un embedding plus petit en 100 dimensions. 
Ensuite, j'ai calculé la distance entre chaque député sur la base de cette embedding à dimension réduite  


Qu'est ce que j'en retire?
De cette methode, on observe une répartition des déuptés sur deux grands axes.
Ceux-ci peuvent être nommé en Majorité/opposition, puis en gauche/droite. 
Aussi, puisque la visualisation ne se base que sur les votes, ça permet d'avoir une vue non biaisé par la communication de chaque politique (on observe ce qu'ils font, pas ce qu'ils disent). 
Ce qu'on observe en plus, c'est que certains déuptés sont plus proche que leur communication semble laisser penser. 
Enfin, c'est un premier pas vers 


---

### About this project
* Python, Javascript
* Packages/Librairies: Pandas, skLearn, plotly, TensorFlow, ReactJS, D3Js 
* Interactive webapp


### Links
* Link to the [webapp](https://spectacular-moonbeam-62dc2d.netlify.app/)
* Link to the [repository](https://github.com/ThomasBench/deputeapp)
