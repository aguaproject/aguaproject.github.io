---
title: Fliers
permalink: /pdf/
---
# Fliers
{% for file in site.static_files %}
  {%- if file.extname == ".pdf" -%}
      - [{{ file.path }}]({{ site.baseurl }}{{ file.path }})
  {%- endif -%}
{% endfor %}
