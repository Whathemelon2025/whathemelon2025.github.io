---
layout: page
title: MLOps
permalink: /MLOps/
---

{% for post in site.posts %}
  {% if post.categories contains 'mlops' %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%Y-%m-%d" }}*

{{ post.excerpt }}

---
  {% endif %}
{% endfor %}
