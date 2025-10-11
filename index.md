---
layout: home
title: Welcome
---
# About Me
Hi, I'm [Your Name]. This is my personal webpage featuring blogs on Physics and Computing, along with my projects. Explore my content below:
- Physics Blog: Insights into quantum mechanics, astrophysics, and more.
- Computing Blog: Tips and tutorials on programming, algorithms, and software development.
- About Me: Learn more about my background and interests.
- GitHub: View my open-source projects.

Recent Posts

Physics

{% for item in site.physics limit:2 %}

[{{ item.title }}]({{ item.url }}) - {{ item.date | date: "%B %d, %Y" }} {% endfor %}

Computing
{% for item in site.computing limit:2 %}
[{{ item.title }}]({{ item.url }}) - {{ item.date | date: "%B %d, %Y" }} {% endfor %}