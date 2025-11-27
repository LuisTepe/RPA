---
layout: default
---

# Archivos del sitio

{% for file in site.static_files %}
- [{{ file.path }}]({{ file.path }})
{% endfor %}
