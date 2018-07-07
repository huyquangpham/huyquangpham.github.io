---
layout: post
title:  "A lucky day"
og-title:  "A lucky day - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2011-11-11 17:28:32 +0700
description: 'A lucky day'
og-description: 'A lucky day'
categories: charactering
imgUrl: "/media/artwork/a-lucky-day.jpg"
imgThumbnailUrl: "/media/artwork/thum/a-lucky-day.jpg"
imgAlt: "A lucky day"
border: no-border
orientation: landscape
tags: luck day
background: gold
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
