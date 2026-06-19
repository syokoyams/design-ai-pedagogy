---
layout: default
title: Updates & Versioning Record (PDF)
nav_order: 14
---

# Updates & Versioning Record (PDF)

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}