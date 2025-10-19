---
layout: page
title: Other Content
permalink: /other/
---
{% for item in site.other %}
- [{{ item.title }}]({{ site.baseurl }}{{ item.url }}) - {{ item.date | date: "%B %d, %Y" }}
{% endfor %}
