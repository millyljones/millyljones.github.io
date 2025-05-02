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
* Ph.D , University of Kent, 2022 - ongoing
* MSc in Computational Applied Mathematics, University of Edinburgh, 2020 - 2021
* BSc in Mathematics, University of Edinburgh, 2017 - 2020
  
Computing Skills
======
* R, Distance, NIMBLE, LaTex

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

Experience
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
