---
layout: archive
title: "About Me"
permalink: /about-me/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* BEng in Computer Science and Mathematics, The Hong Kong University of Science and Technology, 2026 (expected)
* BBA in General Business Management, The Hong Kong University of Science and Technology, 2026 (expected)
* VNU-HCM High School for the Gifted, 2018

Research experience
=====
* June 2024 - now: Research Assistant for Prof. Don Noh
  * Project: Application of Machine Learning to Financial Data, with Doris Yang Zimo
  * Replicate paper [(Re-)imag(in)ing Price Trends](https://economics.yale.edu/research/re-imagining-price-trends)
    * Reconstruct approximately 2.3 million images, with each image contains OHLC chart, volume bar, and moving average line
    * Reconstruct a convolutional neural network (CNN) model that matches the paper's specification
    * Partially train part of training data
  * Code and report: will be updated
  * Tool: Python, plotly, matplotlib, numpy, pandas, keras, tensorflow
* November 2023 - now: Research Assistant for Prof. Edwin Lai
  * Project: International Trade and Foreign Exchange
    * Collect, clean, and maintain datasets and databases for economics-research purposed
    * Extract and link data from multiple databases for analysis
    * Develop models and implement program code (R). Perform statistical analysis, mainly on regression analysis
  * Tool: R, pandas

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
