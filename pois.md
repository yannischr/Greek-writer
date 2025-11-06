---
layout: page
title: Λίστα Συγγραφέων
permalink: /pois/

---

<ul>
  {% for p in site.pois %}
    <li>
      <a href="{{ p.url | relative_url}}">{{ p.title }}</a>
    </li>
  {% endfor %}
</ul>

<div class="hero-bg" aria-hidden="true" style="background-image: url('{{ "/assets/images/writing.png" | relative_url }}'); background-size: cover; background-position: center; height: 320px; transparency:90;"></div>

<style>
.hero-bg { width:100%; display:block; }
@media (max-width:600px){ .hero-bg{ height:180px; } }
</style>
```
