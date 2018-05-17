---
layout: post
title:  "Tôi màu xanh"
date:   2018-04-30 13:28:32 +0700
description: "I just draw myself in green"
categories: charactering
imgUrl: "/media/artwork/T3.jpg"
imgThumbnailUrl: "/media/artwork/thum/T3.jpg"
imgAlt: "M E G R E E N"
frame: 1
border: no-border
orientation: potrait
tags: green self potrait
background: darkgreen
---
<article class="content">
  <img id="c" class="pic {{ if page.frame }} {{ "pic-frame" }} {{ endif }}" src="{{ page.imgUrl | absolute_url }}" alt="{{ page.imgAlt }}" style="background-color: {{ page.background }};" />
  <h3 class="title">{{ page.title }}</h3>
  <p class="des">{{ page.description }}</p>
  <ul class="tags">
    {% for tag in page.tags %}
      <li><a href="#">{{ tag }}</a></li>
    {% endfor %}
  </ul>
</article>
