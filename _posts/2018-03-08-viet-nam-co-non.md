---
layout: post
title:  "Việt Nam có nón lá"
og-title:  "Việt Nam có nón lá - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2018-03-08 00:00:32 +0700
description: "Phụ nữ Việt Nam nhỏ nhắn, dễ thương"
og-description: "Phụ nữ Việt Nam nhỏ nhắn, dễ thương"
categories: cards
imgUrl: "/media/artwork/non-la.jpg"
imgThumbnailUrl: "/media/artwork/thum/non-la.jpg"
imgAlt: "Phụ nữ Việt Nam nhỏ nhắn, dễ thương"
frame: 1
border: border
orientation: potrait
tags: window the-memory
background: darkred
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
