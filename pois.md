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
  body {
  background-color: #2c3e50 !important;
  color: #ecf0f1 !important;  /* ΑΛΛΑΓΗ */
  margin: 0;
  padding: 20px;
}

.wrapper {
  background-color: #34495e !important;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.3);
  color: #ecf0f1 !important;  /* ΠΡΟΣΘΗΚΗ */
}
</style>
```
