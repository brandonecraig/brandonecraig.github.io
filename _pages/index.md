---
layout: defaults/page
permalink: index.html
narrow: true
title: Hi, I'm B. Craig
---

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}
