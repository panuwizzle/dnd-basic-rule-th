---
layout: book
menu: menu-basic-rules
title: ไอเท็มเวทมนต์ (Magic Items)
---
# คลาสต่าง ๆ ใน D&D

{% for item in site.magic-items %}
<a href="{{item.url}}">{{ item.name }}</a>

{% endfor %}