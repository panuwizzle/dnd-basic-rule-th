---
layout: book
menu: menu-basic-rules
title: รายการคาถา
---

# รายการคาถา

{% for spell in site.spells %}
<a href="{{spell.url}}">{{ spell.name }}</a>

{% endfor %}
