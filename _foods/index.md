---
name: Foods
---

{% for food in site.foods %}
  <h2>
    <a href="{{ food.url }}">
      {{ food.name }}
    </a>
  </h2>
  <p>{{ food.content | markdownify }}</p>
{% endfor %}