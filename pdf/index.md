---
title: Fliers
permalink: /pdf/
---
# Fliers
{% for item in site.static_files %}
     {% if item.extname == 'pdf' %}
         <img src="{{ file.url }}" />
     {% endif %}
{% endfor %}
