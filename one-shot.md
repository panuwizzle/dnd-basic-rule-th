---
layout: page
title: One-Shot Adventure list
---

{% for adventure in site.oneshots %}
  <h2>{{ adventure.name }}</h2>
  {{adventure.permalink }}
{% endfor %}