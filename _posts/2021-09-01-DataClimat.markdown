---
title: "DataClimat, a website to raise public awareness on Climat Changes "
layout: post
date: 2021-09-01 12:00
tag: DataViz, WebDev, PR
image: /assets/images/dataclimat.jpg
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: ""
category: project
author: Thomas Benchetrit
externalLink: false
---

This is a project carried out under the supervision of the french member of parliament [Paula Forteza](https://www.linkedin.com/in/paula-forteza-07191895/) and [Louis Magnes](https://www.linkedin.com/in/louis-magnes-91b35169/).

---

In August 2021, the IPCC presented the first part of its latest report in which it makes a clear statement: the effects of global warming will accelerate, regardless of the rate at which greenhouse gas emissions are reduced. In this context, "Every fraction of a degree counts" the report says. This last injunction reminds us of the emergency of the mobilization necessary to radically transform our lifestyles, but also the urgency of making ecology the priority and the heart of decision-making. In this context, scientific data that proves these dramatic developments must be available to the greatest number of people. 
Therefore in order to raise public awareness about those interrogations of paramount importance, the french member of parliament Paula Forteza decided to develop a webapp to beter understand the repercussions of the climat change on the french climat.

The visualisations were produced using to main databases : 
- the Drias database, "les futurs du climat", which "makes available regionalised climate projections produced in French climate modelling laboratories (IPSL, CERFACS, CNRM)". 
- The IPCC database,  taken directly from the first part of the IPCC's sixth report, published in early August 2021. 


The website was designed, both front-end and back-end, using the Dash Plotly framework, which bases itself on the Flask framework for Python, Bootstrap and React for the front-end. On top of it, in order to avoid server-side rendering and latency, the client-side callbacks are written in javascript.

---

### About this project
* Python, Javascript
* Packages/Librairies: Pandas, Dash, plotly, Leaflet
* Interactive Data vizualisations


### Links
* Link to the [website](https://www.dataclimat.fr/). 
* Link to the [repository](https://github.com/ThomasBench/DataClimat). The doc is only in french for the moment.
* You can find the datasets used [here](http://www.drias-climat.fr/) for the DRIAS, and [here](https://www.ipcc.ch/report/ar6/wg1/) for the IPCC.
