---
title: "DataClimat, a website to raise public awareness on Climat Changes "
layout: post
date: 2020-12-17 22:10
tag: DataViz, WebDev, PR
image: /assets/images/EPFL_Logo.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: ""
category: project
author: Thomas Benchetrit
externalLink: false
---

This is a project carried out under the supervision of the french member of parliament [Paula Forteza ](https://www.linkedin.com/in/paula-forteza-07191895/) and [Louis Magnes] (https://www.linkedin.com/in/louis-magnes-91b35169/).

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
* Here's the link to the [website](https://www.dataclimat.fr/). 
* Link to the [repository](https://github.com/EliottZemour/cs-433-project-2-lpmc_dcm).
* The dataset used is London Passenger Mode Choice (LPMC) revealed-preference data. A description of the features can be found [here](https://transp-or.epfl.ch/documents/technicalReports/CS_LPMC.pdf).
* Full details of the framework, dataset, and the models it was used to develop are given in [Hillel et al. (2018)](https://doi.org/10.1680/jsmic.17.00018).