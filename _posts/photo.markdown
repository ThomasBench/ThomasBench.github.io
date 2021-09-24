---
title: "Emotion Based Image Enhancement"
layout: post
date: 2021-06-01 12:00
tag: Computer Vision, Image Enhancement, Python
image: /assets/images/logo_EPFL.jpg
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

Image enhancement is a well-researched field with many papers written on this topic. In this project, we investigate and create an emotion-based image enhancement system by using pre-defined methods and algorithms. This system edits the images to increase the intensity of a given emotion to produce plausible images. 

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
