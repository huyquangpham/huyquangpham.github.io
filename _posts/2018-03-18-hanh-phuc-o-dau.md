---
layout: post
title:  "Tìm hạnh phúc hoài"
og-title: "Tìm hạnh phúc hoài - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2018-03-18 13:28:32 +0700
description: "Cứ tìm tới khi thấy"
og-description: "Cứ tìm tới khi thấy"
categories: charactering
imgUrl: "/media/artwork/where-is-h.jpg"
imgThumbnailUrl: "/media/artwork/thum/where-is-h.jpg"
imgAlt: "Cứ tìm tới khi thấy"
frame: 1
border: no-border
orientation: potrait
tags: hair girl potrait
background: yellow
---
<article class="content">
  <div class="wrapper wrapper-img">
    <img id="c" class="pic {% if page.frame %}{{ "pic-frame" }}{% endif %}" src="{{ page.imgUrl | absolute_url }}" alt="{{ page.imgAlt }}" style="background-color: {{ page.background }}" />
  </div>
  <h3 class="title">{{ page.title }}</h3>
  <p class="des">{{ page.description }}</p>
  <ul class="tags">
    {% for tag in page.tags %}
      <li><a href="#">{{ tag }}</a></li>
    {% endfor %}
  </ul>
</article>
