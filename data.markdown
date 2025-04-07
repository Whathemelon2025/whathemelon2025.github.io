---
layout: page
title: Data
permalink: /Data/
---

{% for post in site.posts %}
  {% if post.categories contains 'data' %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%Y-%m-%d" }}*

{{ post.excerpt }}

---
  {% endif %}
{% endfor %}