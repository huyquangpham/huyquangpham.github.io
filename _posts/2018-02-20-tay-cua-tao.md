---
layout: post
title:  "Tay của tao"
og-title:  "Tay của tao - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2018-02-20 00:28:32 +0700
description: "Just my hand"
og-description: "Just my hand"
categories: charactering
imgUrl: "/media/artwork/my-hand.jpg"
imgThumbnailUrl: "/media/artwork/thum/my-hand.jpg"
imgAlt: "See what!? Huh..."
frame: 1
border: no-border
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
