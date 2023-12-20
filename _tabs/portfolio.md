---
icon: fas fa-briefcase
order: 3
---

{% for post in site.categories.portfolio %}
  {{ post.content }}
{% endfor %}
