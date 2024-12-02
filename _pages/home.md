---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

### Welcome!

I'm a lecturer in artificial intelligence at Manchester Metropoliton Univeristy, and I wanted to share my research and experiences with others. On this blog, I'll be writing about interesting stuff I find in my research, as well as my journey as a lecturer in the UK.

I hope you'll join me on this journey!


### About me

My research interests are focused on nature-inspired optimization and explainable Artificial Intelligence (AI). My research involves the application of nature-inspired algorithms to enhance the optimization of comprehensive machine learning models. At present, my efforts are directed towards employing these models to complex data structures. This aims to facilitate the application of a broader range of white-box models to the domain of complex machine learning.

I have successfully supervised several masters students, and one of her projects has been recognized by the University of Exeter Knowledge Exchange awards. This particular project focuses on utilizing explainability tools to gain insights into the performance of various chemicals in Covid-19 test strips.
 
I hold a PhD in Computer Science from the University of Kent, where my thesis focused on using ant colony optimization (ACO) for stream learning. Specifically, I developed a new pheromone model for ACO-inspired approaches in data mining, and extended the Ant Miner algorithm to create a novel stream mining algorithm.

I also hold an MSc in Computer Science from the American University in Cairo, where my dissertation focused on optimization algorithms for QAP problems.

I enjoy teaching and research, and I am always looking for new ways to apply my skills to solve real-world problems. I worked in the University of Exeter for 2 years, before I moved north, and joined Manchester Metropolitan University.



### Posts

<div class="jumbotron">
{% for article in site.data.posts %}
<b>{{ article.date }}</b>
{{ article.headline }}
<p>{{ article.abstract }}</p>
<a href="{{ site.url }}{{ site.baseurl }}{{ article.file }}">... read</a> 
{% endfor %}
</div>
