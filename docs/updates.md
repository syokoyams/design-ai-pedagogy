---
layout: default
title: Updates & Versioning Record
nav_order: 14
---

# Updates & Versioning Record

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}