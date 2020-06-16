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
* BEng in Communication Engineering, Huazhong University of Science and Technology (HUST), 2012-2016
* PhD in Computer Science, Hong Kong University of Science and Technology (HKUST), 2016-2021 (expected)

 

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>