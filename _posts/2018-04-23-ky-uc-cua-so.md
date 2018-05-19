---
layout: post
title:  "Ký ức Cửa sổ"
og-title:  "Ký ức Cửa sổ - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2018-04-23 00:28:32 +0700
description: "Bất chợt đôi khi gặp lại ký ức"
og-description: "Bất chợt đôi khi gặp lại ký ức"
categories: charactering
imgUrl: "/media/artwork/T1.jpg"
imgThumbnailUrl: "/media/artwork/thum/T1.jpg"
imgAlt: "Bất chợt đôi khi gặp lại ký ức"
frame: 1
border: border
orientation: potrait
tags: window the-memory
background: darkred
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
