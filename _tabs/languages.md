---
icon: fas fa-language
order: 5
---

{% for post in site.categories.languages %}
  {{ post.content }}
{% endfor %}
