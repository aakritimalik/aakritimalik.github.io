---
permalink: /outreach/
title: "Outreach"
excerpt: "One-line description here"
header:
  overlay_image: header/mindfulllyme.jpg
  overlay_filter: 0.2 # same as adding an opacity of 0.2 to a black background
  caption: "Photo: A. Malik"
author_profile: true
redirect_from: 
  - /outreach/talks/
  - /outreach/teaching/
---

{% include base_path %}


## Instagram Page

<div style="float: left; margin-right: 10px; width: 800px">
    <a href="https://www.instagram.com/p/B_jkE9ejVsB/" title="https://www.instagram.com/p/B_jkE9ejVsB/"><img src="/images/mindfullly.png"></a>
</div>
</br>


<div style="float: left; margin-right: 10px; width: 800px">
    <a href="https://www.instagram.com/p/B_jkE9ejVsB/" title="https://www.instagram.com/p/B_jkE9ejVsB/"><img src="/images/mind_2.png"></a>
</div>
</br>

<div style="float: left; margin-right: 10px; width: 800px">
    <a href="https://www.instagram.com/p/B_jkE9ejVsB/" title="https://www.instagram.com/p/B_jkE9ejVsB/"><img src="/images/mind_3.png"></a>
</div>
</br>

<div style="float: left; margin-right: 10px; width: 800px">
    <a href="https://www.instagram.com/p/B_jkE9ejVsB/" title="https://www.instagram.com/p/B_jkE9ejVsB/"><img src="/images/mind_4.png"></a>
</div>
</br>


{% if site.talkmap_link == true %}
  <i class="fas fa-map-marked-alt"></i> You can also see a [map of all the places I've given a talk](/outreach/talkmap/).
{% endif %}{: .notice--info}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}


## Teaching
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
