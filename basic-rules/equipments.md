---
layout: book
menu: menu-basic-rules
title: อุปกรณ์ (Equipments)
---
# อุปกรณ์ต่าง ๆ ใน D&D

{% for item in site.equipments %}
<a href="{{item.url}}">{{ item.name }}</a>

{% endfor %}