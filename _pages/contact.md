---
permalink: /contact/
title: "Contact"
excerpt: "Contact details and some links."
author_profile: true
redirect_from: 
  - 
---

{% include base_path %}

### Office
<i class="fas fa-building" aria-hidden="true"></i>&nbsp;&nbsp;Middlemore Hospital, Auckland, New Zealand<br />

<i class="fas fa-envelope" aria-hidden="true"></i>&nbsp;&nbsp;<a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a><br />


### Online

{% if site.author.instagram %}
  <i class="fab fa-instagram" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://instagram.com/{{ site.author.instagram }}">Instagram</a><br />
{% endif %}
{% if site.author.linkedin %}
  <i class="fab fa-linkedin" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a><br />
{% endif %}
{% if site.author.researchgate %}
  <i class="ai ai-researchgate-square" aria-hidden="true"></i>&nbsp;&nbsp;<a href="https://www.researchgate.net/profile/{{ site.author.researchgate }}">ResearchGate</a><br />
{% endif %}
{% if site.author.orcid %}
  <i class="ai ai-orcid"></i>&nbsp;&nbsp;<a href="https://orcid.org/{{ site.author.orcid }}">ORCID</a><br />
{% endif %}