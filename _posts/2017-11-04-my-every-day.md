---
layout: post
title:  "My everyday"
og-title:  "My everyday - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2017-11-04 18:28:32 +0700
description: 'My everyday'
og-description: 'My everyday'
categories: charactering
imgUrl: "/media/artwork/my-every-day.jpg"
imgThumbnailUrl: "/media/artwork/thum/my-every-day.jpg"
imgAlt: "My everyday"
frame: 1
border: no-border
orientation: potrait
tags: everyday tired work
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
