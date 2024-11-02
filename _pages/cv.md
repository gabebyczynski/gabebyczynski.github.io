---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Psychology, Trinity College Dublin, University of Dublin (IE), 2024
* M.Sc. (Distinction) Brain Imaging and Cognitive Neuroscience, University of Birmingham (UK), 2022
* B.Sc. (Distinction) Neuroscience and Biology Combined Honours, Carleton University, (CAN), 2021
  
Skills
======
* Electroencephalography, Magnetoencephalography, (Functional) Magnetic Resonance Imaging
* Behaviour and Physiological Recording (GSR, Pupillometry, HRV)
* Machine learning prediction for clinical outcomes

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
