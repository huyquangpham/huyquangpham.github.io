---
layout: post
title:  "A capital student"
og-title:  "A capital student - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2018-01-04 17:28:32 +0700
description: 'A capital student'
og-description: 'A capital student'
categories: charactering
imgUrl: "/media/artwork/a-captial-student.jpg"
imgThumbnailUrl: "/media/artwork/thum/a-captial-student.jpg"
imgAlt: "A capital student"
frame: 1
border: border
orientation: potrait
tags: capital student girl
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
