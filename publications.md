---
title: Publications
layout: default
---

# Publications

[comment]: <> (Adding/Removing Publications from the )
[comment]: <> (1. First, make sure this is an actual publication, and not a poster from a conference.)
[comment]: <> (2. When in doubt, ask Dr. Olschanowsky if it qualifies to be counted.)
[comment]: <> (3. To add new, add most recent to the top of the list at /_data/publications.yml)
[comment]: <> (4. Search for new articles by going to this link https://scholar.google.com/citations?hl=en&user=V6gXo9IAAAAJ&view_op=list_works&sortby=pubdate# for Dr. Olschanowsky's publications.)
[comment]: <> (5. Add your new items as the originals were, with most recent being on top.)
[comment]: <> (6. The only required fields are Title, and Authors.)
[comment]: <> (7. If year, journal, conference, and/or publisher cannot be found, they will be skipped.)
[comment]: <> (8. Following the older examples will be the easiest way to ease into this.)

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