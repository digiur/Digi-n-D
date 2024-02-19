---
tags:
- Jekyll
- GitHub Pages
- Blog
---
# Digi-n-D
GM Materials For DiginD Campaigns


[shop](locations/aubreys-peculiarities-shoppe.md)

{% if site.tags != "" %}
  {% include collecttags.html %}
{% endif %}

{% for tag in page.tags %}
    {{ tag }}
{% endfor %}