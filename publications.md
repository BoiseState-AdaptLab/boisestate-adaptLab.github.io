---
title: Publications
layout: default
---

# Publications

<br>

{% for item in site.data.publications.publications %}

{% if item.url %}
## [{{ item.title }}]({{ item.url }})
{% else %}
## {{ item.title }}
{% endif %}

{{ item.authors }}. {% if item.year %}{{ item.year }}. {% endif %} {% if item.journal %}{{ item.journal }}. {% endif %} {% if item.conference %}{{ item.conference }}. {% endif %} {% if item.publisher %}{{ item.publisher }}. {% endif %}

<br>

{% endfor %}