---
layout: page
title: One-Shot Adventure list
---

{% for adventure in site.one-shot %}
[{{ adventure.name }}]({{adventure.url }})

{% endfor %}
