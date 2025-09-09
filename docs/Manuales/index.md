---
layout: default
title: "Manuales DLR"
nav_order: 4
---

# 📄 Manuales DLR

<!-- Índice automático: lista todos los PDFs en /docs/Manuales/ -->
<ul>
{% assign pdfs = site.static_files | where_exp: "f", "f.extname == '.pdf' or f.extname == '.PDF'" | sort: "name" %}
{% for f in pdfs %}
  {% if f.path contains '/docs/Manuales/' %}
    <li>
      <a href="{{ f.path | relative_url }}" target="_blank" rel="noopener">
        {{ f.name
            | replace: '_',' '
            | replace: '-',' '
            | replace: '.pdf',''
            | replace: '.PDF',''
            | capitalize }}
      </a>
    </li>
  {% endif %}
{% endfor %}
</ul>
