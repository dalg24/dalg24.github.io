---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* Spring 2014: Computational Scientist
  * Oak Ridge National Laboratory
  
Skills
======
* Computer Programming
  * C++: expert, ISO C++ standards committee member since 2018
* Software Development
  * 15 years of contribution to open-source software for science
* Languages
  * English and German: fluent
  * French: native

Education
======
* Ph.D in Nuclear Engineering, Texas A&M University, USA, 2014
* M.S. in Physics, Karlsruhe Institute of Technology, Germany, 2010
* M.Eng. in Physics Engineering, Grenoble Institute of Technology, France, 2009

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
  
Service and leadership
======
* Led the development and launch of the [CppCon Scientific Computing Track](https://cppcon.org/scientific-computing-track/), serving as Chair since 2022.
* [High Performance Software Foundation (HPSF)](https://hpsf.io/about/) Governing Board: Technical Advisory Council representative.
