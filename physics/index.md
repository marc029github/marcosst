---
layout: page
title: Physics Blog
permalink: /physics/
---
{% for item in site.physics %}
- [{{ item.title }}]({{ site.baseurl }}{{ item.url }}) - {{ item.date | date: "%B %d, %Y" }}
{% endfor %}
