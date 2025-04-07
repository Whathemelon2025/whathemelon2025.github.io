---
layout: page
title: GenAI
permalink: /GenAI/
---

{% for post in site.posts %}
  {% if post.categories contains 'gen' %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%Y-%m-%d" }}*

{{ post.excerpt }}

---
  {% endif %}
{% endfor %}

