---
layout: page
title: Computing Blog
permalink: /computing/
---
{% for item in site.computing %}
- [{{ item.title }}]({{ site.baseurl }}{{ item.url }}) - {{ item.date | date: "%B %d, %Y" }}
{% endfor %}
