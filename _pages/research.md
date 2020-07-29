---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research fits into two clear, but interconnected tracks. Please click on the links below to see more detail on projects associated with each track.
{% for research in site.research %}
<h2> <a href="{{ research.url }}"> {{ research.title }} </a> </h2>
<p class="post-excerpt">{{ research.description }}</p>
{% endfor %}

