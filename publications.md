---
title: Publications
layout: default
---

# Publications

<br>

{% for item in site.data.publications.publications %}
   
## [{{ item.title }}]({{ item.url }})

{{ item.authors }}. {{ item.year }}. {% if item.journal %}{{ item.journal }}. {% endif %} {% if item.conference %}{{ item.conference }}. {% endif %} {% if item.publisher %}{{ item.publisher }}. {% endif %}

<br>

{% endfor %}