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
* Ph.D in NLP/Computational Linguistics, Le Mans Université, ongoing
* M.S. in Computational Linguistics, Université Bordeaux Montaigne, 2022
* B.S. in Linguistics, Université Bordeaux Montaigne, 2020

Work experience
======
* Spring 2022: Research Assistant
  * Le Mans Université
  * Supervisor: Nicolas Dugué


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
  

