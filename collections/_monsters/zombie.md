---
layout: page
title: Zombie
name: Zombie
type: Medium undead
cr: 1/4
---

{% capture stat_block %}
# Zombie
_Medium undead, neutral evil_
{:.redunder}

**Armor Class** 8  
**Hit Points** 22 (3d8 + 9)  
**Speed** 20 ft.
{:.redunder}

| STR     | DEX    | CON     | INT    | WIS    | CHA    |
| ------- | ------ | ------- | ------ | ------ | ------ |
| 13 (+1) | 6 (−2) | 16 (+3) | 3 (−4) | 6 (−2) | 5 (−3) |
{:.redtable}

**Saving Throws** Wis +0  
**Damage Immunities** poison  
**Condition Immunities** poisoned  
**Senses** darkvision 60 ft., passive Perception 8  
**Languages** understands the languages it knew in life but can't speak  
**Challenge** 1/4 (50 XP)
{:.redunder}

**_Undead Fortitude._** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

### Actions
{:.redslim}

**_Slam._** _Melee Weapon Attack:_ +3 to hit, reach 5 ft., one target. _Hit:_ 4 (1d6 + 1) bludgeoning damage.

{% endcapture %}

{% include monster.html content=stat_block %}
