---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

### Welcome!

I'm a lecturer in Computer Science at the University of Exeter, and I'm passionate about sharing my research and experiences with others. On this blog, I'll be writing about interesting stuff I find in my research, as well as my journey as a lecturer in the UK.

I'll also be sharing my thoughts on current events in the tech industry, and providing tips and advice for students and researchers. I hope you'll join me on this journey!


### About me



I hold a PhD in Computer Science from the University of Kent, where my thesis focused on using ant colony optimization (ACO) for stream learning. Specifically, I developed a new pheromone model for ACO-inspired approaches in data mining, and extended the Ant Miner algorithm to create a novel stream mining algorithm.

I also hold an MSc in Computer Science from the American University in Cairo, where my dissertation focused on optimization algorithms for QAP problems.

I am passionate about teaching and research, and I am always looking for new ways to apply my skills to solve real-world problems. 



### Posts

<div class="jumbotron">
{% for article in site.data.posts %}
<b>{{ article.date }}</b>
{{ article.headline }}
<p>{{ article.abstract }}</p>
<a href="{{ site.url }}{{ site.baseurl }}{{ article.file }}">... read</a> 
{% endfor %}
</div>
