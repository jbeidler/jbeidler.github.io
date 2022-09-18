---
name: Frequently Asked Questions
---

<ul>
{% for item in site.faqs %}
  <li>
    <a href="{{ item.url }}">
      {{ item.name }}
    </a>
  </li>
{% endfor %}
</ul>