---
layout: post
title:  "Không gặp lại"
og-title: "Không gặp lại - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2018-05-19 13:28:32 +0700
description: "I met you, and I said that in my mind"
og-description: "I met you, and I said that in my mind"
categories: charactering
imgUrl: "/media/artwork/slow-down.jpg"
imgThumbnailUrl: "/media/artwork/thum/slow-down.jpg"
imgAlt: "I met you, and I said that in my mind"
frame: 1
border: border
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
