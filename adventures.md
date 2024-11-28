---
layout: page
title: เนื้อเรื่องการผจญภัย (Adventures)
---

ในการเล่นเกม ดันเจี้ยนมาสเตอร์ (Dungeon Master) หรือ DM จะเป็นคนเล่าเรื่องและให้ผู้เล่น (Player) ตัดสินใจไปตามสถานการณ์ เรื่องที่ DM เล่านี้เราเรียกว่า การผจญภัย (Adventure) เนื้อเรื่องสั้น ๆ เราจะเรียกว่า วันช็อต (one-shot) อาจจะเป็นภาระกิจเดียว ใช้เวลา 3-4 ชม. ก็เล่นจบ ส่วนเนื้อเรื่องยาวจะเรียกว่าแคมเปญ (Campaign) มีหลายภาระกิจและต้องเล่นหลายเซสชัน (เซสชัน (Session) คือชื่อเรียกช่วงเวลาที่เล่นเกมแต่ละครั้ง) ตัวละครจะมีการเลื่อนระดับ (level) โตขึ้นแข็งแกร่งขึ้น แคมเปญอาจจะมีตั้งแต่ 4-5 เซสชันไปจนถึงหลายสิบเซสชัน บางกลุ่มเล่นกันยาวนานเป็นสิบปี สนุกจนน่าอิจฉา

## การผจญภัยสั้น (One-shot)

<div class="columns">
  {% for adventure in site.one-shot %}
  <div class="column is-3">
  <div class="card">
  <div class="card-image">
    <figure class="image is-4by3">
      <img
        src="{{ adventure.feature_image }}"
        alt="Placeholder image"
      />
    </figure>
  </div>

  <div class="card-content">
        <h1 class="title is-5"><a href="{{ adventure.url }}">{{ adventure.name }}</a></h1>
            {{ adventure.short_description }}
  </div>
    
  </div>
  </div>
  {% endfor %}
</div>
