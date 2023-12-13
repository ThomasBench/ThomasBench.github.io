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

### Overview
DeputeMap is an innovative project designed to visualize the voting affinities among Members of Parliament (MPs) during the French 15th legislature. The intent of the project is to uncover the voting patterns and alliances that are crucial to understanding the political dynamics within the legislative body. By focusing solely on empirical voting data, DeputeMap provides an analysis that eschews the typical biases introduced by political rhetoric and public personas, laying bare the genuine stances and coalitions that shape parliamentary proceedings.

### Objective
The primary goal of this project was to investigate and graphically represent the political currents underpinning the voting behavior of MPs. Specifically, the analysis aimed to answer research questions around the formation of political blocs and ideological spectrums, exploring how these manifest in legislative behavior and whether publicly avowed positions correspond with actual voting practices.

### Methodology
To achieve this, the project bases itself on all recorded votes cast by MPs throughout the 15th Parliament. These votes—indicating whether an MP voted for, against, or abstained on a given matter—served as the foundation for constructing a comprehensive MP embedding, initially spanning an N-dimensional space where N equates to the total number of votes analyzed.

Subsequent to the creation of this high-dimensional embedding, a process of dimensionality reduction was implemented, streamlining the complex data into a more manageable 100-dimensional representation. This refined construct allowed for the calculation of distances between individual MPs, measured on the basis of their legislative voting proximity.

### Results
From the application of these analytical techniques, DeputeMap presents a visualization that positions MPs along two principal axes. The first axis distinguishes between the Majority and Opposition, illustrating the primary division that typically defines legislative bodies. The second axis offers a traditional Left/Right political spectrum. This demarcation not only clarifies ideological standings but also sometimes reveals surprising affinities between MPs whose public personas and communication strategies might suggest greater distance.

### Impact and Applications
Deploying open data to achieve its objectives, DeputeMap serves as both an exposé of latent political fault lines and a strategic tool for political actors. It equips MPs and political factions with insights that could facilitate the identification of unexpected yet potentially fruitful alliances—a particularly valuable resource in the context of a fractured parliamentary landscape.

For researchers and observers of the political scene, DeputeMap unlocks a quantitative approach to understanding legislative behavior, free from the distortive effects of subjective interpretation. It stands as a testament to the power of data-driven analysis in contemporary political discourse and has the potential to inform both academic research and practical political strategy. It also provides a comprehensive tool for MPs and political forces to identify potential allies for subsequent votings. 



---

### About this project
* Python, Javascript
* Packages/Librairies: Pandas, skLearn, plotly, TensorFlow, ReactJS, D3Js 
* Interactive webapp


### Links
* Link to the [webapp](https://spectacular-moonbeam-62dc2d.netlify.app/)
* Link to the [repository](https://github.com/ThomasBench/deputeapp)
