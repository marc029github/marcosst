---
layout: page
title: Welcome to My Page
---

Hi, I'm Marcos. This is my personal webpage featuring activities, notes, hacking and projects, most of them on the topics of Computing and Physics. Explore my content below:

- [Physics Blog]({{ site.baseurl }}/physics/): Things I study or work on in the realm of physics.
- [Computing Blog]({{ site.baseurl }}/computing/): Mostly embedded software, hardware design, AI and hacking.
- [Others Blog]({{ site.baseurl }}/other/): Other content.
- [About Me]({{ site.baseurl }}/about/): Learn more about my background and interests.
- [GitHub](https://github.com/marc029github): View my open-source projects.

## Recent Posts

### Physics
{% for item in site.physics limit:2 %}
- [{{ item.title }}]( {{ site.baseurl }}{{ item.url }}  ) - {{ item.date | date: "%B %d, %Y" }}
{% endfor %}

### Computing
{% for item in site.computing limit:2 %}
- [{{ item.title }}]({{ site.baseurl }}{{ item.url }}) - {{ item.date | date: "%B %d, %Y" }}
{% endfor %}

### Other
{% for item in site.other limit:2 %}
- [{{ item.title }}]({{ site.baseurl }}{{ item.url }}) - {{ item.date | date: "%B %d, %Y" }}
{% endfor %}

## Recent Posts
I am @marc029fernande on X. Also find my resume at [LinkedIn](https://www.linkedin.com/in/marcosfernandez0307)

# Contact Information

You can reach me via email:

[fernanm2@proton.me](mailto:fernanm2@proton.me)
