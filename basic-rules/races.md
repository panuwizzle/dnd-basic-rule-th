---
layout: book
menu: menu-basic-rules
title: เผ่าพันธุ์ (Races)
---
# เผ่าพันธุ์ต่าง ๆ ใน D&D

{% for race in site.races %}
<a href="{{race.url}}">{{ race.name }}</a>

{% endfor %}