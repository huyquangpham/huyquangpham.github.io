---
layout: post
title:  "Đời ai cũng có..."
og-title:  "Đời ai cũng có... - Huy Quang Pham - Character Design, Hobbyist Artist"
date:   2018-05-23 00:28:32 +0700
description: '"Phút chốc người lỡ nói vậy. Ta quen chẳng trách người đâu" - Câu chuyện của một người nào đó..'
og-description: '"Phút chốc người lỡ nói vậy. Ta quen chẳng trách người đâu" - Câu chuyện của một người nào đó..'
categories: charactering
imgUrl: "/media/artwork/doi-ai-cung-co-giay-phut-trot-yeu-dai-kho.jpg"
imgThumbnailUrl: "/media/artwork/thum/doi-ai-cung-co-giay-phut-trot-yeu-dai-kho.jpg"
imgAlt: "Phút chốc người lỡ nói vậy. Ta quen chẳng trách người đâu"
border: no-border
orientation: potrait
tags: sad but happy
background: darkblue
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
