---
icon: fas fa-bars
order: 9
---

{% for post in site.categories.other-posts %}
  {{ post.content }}
{% endfor %}
