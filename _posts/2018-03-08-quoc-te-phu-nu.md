---
layout: post
title:  "[8 3] Smoky Women"
og-title:  "Tay của tao - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2018-03-08 00:28:32 +0700
description: "Chào mừng ngày Quốc tế phụ nữ 8/3"
og-description: "Chào mừng ngày Quốc tế phụ nữ 8/3"
categories: cards
imgUrl: "/media/artwork/woman-day.jpg"
imgThumbnailUrl: "/media/artwork/thum/woman-day.jpg"
imgAlt: "Chào mừng ngày Quốc tế phụ nữ 8/3"
frame: 1
border: border
orientation: potrait
tags: hand self
background: yellow
---
<article class="content">
  <div class="wrapper wrapper-img">
    <img id="c" class="pic {{ if page.frame }} {{ "pic-frame" }} {{ endif }}" src="{{ page.imgUrl | absolute_url }}" alt="{{ page.imgAlt }}" style="background-color: {{ page.background }}" />
  </div>
  <h3 class="title">{{ page.title }}</h3>
  <p class="des">{{ page.description }}</p>
  <ul class="tags">
    {% for tag in page.tags %}
      <li><a href="#">{{ tag }}</a></li>
    {% endfor %}
  </ul>
</article>
