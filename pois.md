---
layout: page
title: POIs List
permalink: /pois/

---

<ul>
  {% for p in site.pois %}
    <li>
      <a href="{{ p.url }}">{{ p.title }}</a>
    </li>
  {% endfor %}
</ul>
