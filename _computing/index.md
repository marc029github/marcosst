
layout: page   title: Computing Blog   permalink: /computing/
{% for item in site.computing %}     {{ item.title }}     {{ item.excerpt }}   {% endfor %}