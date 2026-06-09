---
layout: default
title: Updates
nav_order: 13
---

# Updates

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}