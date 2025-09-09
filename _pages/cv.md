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

* Ph.D, École Polytechnique Fédérale de Lausanne, 2026 (expected)
* M.A. Individualized study in Mathematics and Music, New York University, 2020
* B.S. Mathematics with minor in Music, University of California San Diego, 2012

<!-- Work experience
====== -->
<!-- * Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git -->
  
Skills
======

* Programming: Haskell, Python, LaTeX
* Language: English, Chinese
* Music: Piano (Jazz)

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

* Reviewer for TISMIR Journal (2024)
* Reviewer for JOSS Journal (2024)
