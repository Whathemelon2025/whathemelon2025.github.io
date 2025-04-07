---
layout: page
title: VisionAI
permalink: /VisionAI/
---

{% for post in site.posts %}
  {% if post.categories contains 'vision' %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%Y-%m-%d" }}*

{{ post.excerpt }}

---
  {% endif %}
{% endfor %}
