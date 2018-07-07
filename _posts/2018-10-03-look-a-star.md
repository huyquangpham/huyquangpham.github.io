---
layout: post
title:  "Look! A star.."
og-title:  "Look! A star.. - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2017-10-03 11:28:32 +0700
description: 'Look! A star..'
og-description: 'Look! A star..'
categories: cards
imgUrl: "/media/artwork/look-a-star.jpg"
imgThumbnailUrl: "/media/artwork/thum/look-a-star.jpg"
imgAlt: "Look! A star.."
frame: 1
border: no-border
orientation: potrait
tags: look star beach
background: grey
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
