---
layout: page
---

Goblin
{% capture monster_stat %}
<h3>Monster Name</h3>
<p>HP: 40</p>
<p>AC: 16</p>
{% endcapture %}

{% include monster.html content=monster_stat %}
