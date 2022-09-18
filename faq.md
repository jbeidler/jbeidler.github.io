---
name: Frequently Asked Questions
---

<ul>
{% for faq in site.faqs %}
  <li>
    <a href="{{ faq.url }}">
      {{ faq.name }}
    </a>
  </li>
{% endfor %}
</ul>