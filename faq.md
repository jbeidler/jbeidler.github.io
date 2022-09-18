---
name: Frequently Asked Questions
---

<ul>
{% for item in site.faq %}
  <li>
    <a href="{{ item.url }}">
      {{ item.name }}
    </a>
  </li>
{% endfor %}
</ul>