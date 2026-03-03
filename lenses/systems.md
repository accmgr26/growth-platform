---
layout: page
title: Systems Lens
permalink: /lenses/systems/
---

## Systems-Oriented Entries

{% for post in site.tags.systems %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %B %Y" }}
{% endfor %}
