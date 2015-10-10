---
layout: archive
permalink: /
title: "Latest Posts"
image:
  feature: us-choro-long.png
feature:
  visible: true
  headline: "Featured Posts"
  category: articles
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-list.html %}
{% endfor %}
</div><!-- /.tiles -->
