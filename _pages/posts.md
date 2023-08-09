---
title: "posts"
layout: textlay
sitemap: false
permalink: /posts/
---

## Posts

<div class="jumbotron">
{% for article in site.data.posts %}
<b>{{ article.date }}</b>
{{ article.headline }}
<p>{{ article.abstract }}</p>
<a href="{{ site.url }}{{ site.baseurl }}{{ article.file }}">... read</a> 
{% endfor %}
</div>
