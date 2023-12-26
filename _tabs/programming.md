---
icon: fas fa-code
order: 4
---

{% for post in site.categories.programming %}
  {{ post.content }}
{% endfor %}
