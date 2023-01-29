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
* B.S. in Applied Math & Civil Engineering, University of Akron, 2008
* M.S. in Civil Engineering, Purdue University, 2009
* M.S. in Applied Math, University of Arizona, 2022
* Ph.D in Applied Math, University of Arizona, 2024 (expected)

Work experience
======
* 2019-present: Senior Data Scientist
    * Tucson, AZ
    * Research and develop machine learning algorithms that meet client requirements
    * Apply mathematical modeling principles to diverse problem areas
    * Write technical reports and present findings to clients

* 2009-2019: Data Scientist
    * Various locations
    * Design statistics to recover unknown features and parameters
    * Write internal peer-reviewed technical articles
    * Certified Adjunct Faculty Instructor

Skills
======
* Machine Learning
    * Computer vision
    * Architecture search
    * Bayesian modeling
* Data Science
  * Data cleaning
  * Visualization
  * Robust statistics
* Programming
    * Python
    * C
    * Fortran
    * And more esoteric languages

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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
