---
name: Foods
---

<ul>
{% for food in site.foods %}
  <li>
    <a href="{{ food.url }}">
      {{ food.name }}
    </a>
  </li>
{% endfor %}
</ul>