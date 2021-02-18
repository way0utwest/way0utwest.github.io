---
layout: defaults/page
permalink: index.html
narrow: true
title: Steve Jones
---

{% include components/intro.md %}

This site contains a list of projects, posts, and other items related to Steve Jones' career.

## Projects

[These are a list of projects]({{ site.baseurl }}{% link list/projects.md %}) that Steve is working on. Some of these are related to Redgate Software, and some are not.

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


