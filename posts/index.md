---
layout: default
permalink: /posts
title: "Latest Posts"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
