---
layout: page
title: Physics Blog
permalink: /physics/
---
{% for item in site.physics %}
- [{{ item.title }}]({{ item.url }}) - {{ item.date | date: "%B %d, %Y" }}
{% endfor %}