---
layout: defaults/page
permalink: index.html
narrow: true
title: Way0utwest
---

## Steve Jones

{% include components/intro.md %}

This is Steve Jones site for his career.


<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


