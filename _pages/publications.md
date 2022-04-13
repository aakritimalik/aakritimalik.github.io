---
permalink: /publications/
title: "Publications"
excerpt: "List of academic publications."
header:
  overlay_image: header/header3.jpg
  overlay_filter: 0.2 # same as adding an opacity of 0.2 to a black background
  caption: "Photo: Jacek Cisło"
author_profile: true
redirect_from: 
  - 
---

{% include base_path %}

## Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

