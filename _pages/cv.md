---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- Click [here](/cv-print/) for a printable version or [download a PDF](/files/cv-print.pdf).<br /><br /><br /> -->

<h2 align="center">{{ site.author.name }}</h2>
<h3 align="center" style="margin: 0px auto 20px;">M.Sc.</h3>
<p align="center" style="margin: auto; width: 80%">{{ site.author.bio }}</p>

<p align="center"><i class="fas fa-envelope" aria-hidden="true"></i>&nbsp;<a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a> &#124; <i class="fas fa-desktop" aria-hidden="true"></i>&nbsp;<a href="{{ site.author.uri }}">{{ site.author.uri | remove: "https://" }}</a> &#124; <i class="fab fa-twitter" aria-hidden="true"></i>&nbsp;<a href="https://twitter.com/{{ site.author.twitter }}">@{{ site.author.twitter }}</a></p>

Education
======
* **MPhil. in Clinical Psychology**, National Institute of Mental Health and Neuro Sciences (NIMHANS), Bangalore, 2015
  + Dissertation title: Pathways-to- care, Awareness about Child Psychiatric Conditions and Expectations from Mental Health Professionals
* **MA in Psychology (Psycho Social Clinical Studies)**, Ambedkar University, New Delhi, 2012
* **BA in Psychology (Honours)**, Jesus and Mary College, University of Delhi, New Delhi, 2010

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
