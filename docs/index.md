---
permalink: /
---

{{ site.description }}
{: .lead }

### Proyectos

<ul>
{% assign pages = site.pages | where_exp: "item", "item.title" %}
{% for page in pages %}
  <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>
