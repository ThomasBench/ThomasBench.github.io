---
title: BotApettit, a free-food bot!
layout: post
date: 2023-05-01 12:00
tag:  Python, API
image: /assets/images/botapettit.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: ""
category: project
author: Thomas Benchetrit
externalLink: false
---

### Overview:
BotApettit is an solution to address the challenge of finding free food events on campus. The project utilizes web scraping and a Large Language Model (LLM) to curate and sort these events, providing a simple and reliable method for users to be informed about opportunities to enjoy free food.
Presented at SIGTBD'23, CSAIL's joke conference
---


### Goal:
The main goal of BotApettit is to help students and researchers to access a healthy and regular diet. By identifying and cataloging events offering free food, the project aims to provide a convenient platform that allows users to plan ahead and attend these events.

### Methodology:
BotApettit utilizes two main steps: scrapping and classification. The scrapping process involves using the BeautifulSoup python package to extract data from the MIT calendar website. While the current implementation focuses on the MIT calendar, future updates will include other calendars such as CSAIL, Sloan, Media Lab, and student groups. Each event is scraped and converted into a readable format, including details like the date, time, location, and description of the event.

Once the events are scraped, classification is performed using large language models, specifically GPT 3.5. The project leverages the power of these models to infer the probability of free food being available at each event. A query is fed to ChatGPT, asking it to estimate the likelihood of free food based on the event description. The resulting probability is then used to classify the event as either free-food or not-free-food, with a threshold of 0.5 determining the classification.

The list of events curated, each day the BotApettit SlackBots post the list of the events with all the necessary challenge into the Lab Slack channel
### Interest and Application:
By aggregating and sorting free food events, BotApettit offers a solution that not only helps users access nourishment but also expands their social horizons. By attending these events, users may discover unexpected gatherings and opportunities to connect with their peers..
---

### About this project
* Python
* Packages/Librairies: BeautifulSoup, OpenAI API, Slack API 
* 


### Links
* Link to the [report](/assets/projects/sigtbd23-paper8.pdf)
* Link to the [Conference](http://sigtbd.csail.mit.edu/)
