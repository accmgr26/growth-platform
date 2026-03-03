---
layout: page
title: Journal
permalink: /journal/
---

## Structured Entries

{% for post in site.categories.journal %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %B %Y" }}
{% endfor %}
