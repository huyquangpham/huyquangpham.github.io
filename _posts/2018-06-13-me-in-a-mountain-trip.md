---
layout: post
title:  "Me in a mountain trip"
og-title:  "Me in a mountain trip - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2018-06-13 00:28:32 +0700
description: 'Me in a mountain trip'
og-description: 'Me in a mountain trip'
categories: charactering
imgUrl: "/media/artwork/me-in-a-mountain-trip.jpg"
imgThumbnailUrl: "/media/artwork/thum/me-in-a-mountain-trip.jpg"
imgAlt: "Me in a mountain trip"
border: no-border
orientation: potrait
tags: trip me self
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
