---
title: Fliers
permalink: /pdf/
---
# Fliers
<ul>
{% for file in site.static_files %}
  {%- if file.extname == ".pdf" -%}
      <li><a href="/pdf?u={{ file.name }}">{{ file.name }}{{ file.extname }}</a></li>
  {%- endif -%}
{% endfor %}
</ul>
