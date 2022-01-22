---
permalink: /publications/
title: "Publications"
excerpt: "List of academic publications."
header:
  overlay_image: header/header3.jpg
  overlay_filter: 0.2 # same as adding an opacity of 0.2 to a black background
  caption: "Photo: J. Garbe"
author_profile: true
redirect_from: 
  - /publications/articles/
---

{% include base_path %}

## Peer-Reviewed Publications
{% if site.author.researchgate and site.author.googlescholar and site.author.orcid %}
  <div class="notice--info social-icons">You can also find my articles on: <a href="https://scholar.google.com/citations?user={{ site.author.googlescholar }}"><i class="fas fa-graduation-cap"></i> Google Scholar</a> &#124; <a href="https://www.researchgate.net/profile/{{ site.author.researchgate }}"><i class="ai ai-researchgate-square" aria-hidden="true"></i> ResearchGate</a> &#124; <a href="https://orcid.org/{{ site.author.orcid }}"><i class="ai ai-orcid"></i> ORCID</a></div>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

