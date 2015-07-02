---
layout: home 
permalink: /
title: Latest posts
image:
  feature: "main.jpg"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
