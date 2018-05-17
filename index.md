---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% for post in site.posts | sort_by: "date" %}
  <div class="item item-{{ post.border }}">
    <a href="{{ post.url | absolute_url }}" class="decoration" style="background-image: url('{{ post.imgThumbnailUrl }}')"></a>
    <div class="literature">
      <h3 class="title">{{ post.title }}</h3>
      <div class="des">
        <h5>{{ post.date | date: '%B %d, %Y' }}</h5>
        <ul class="hash-tags">
          {% for tag in post.tags %}
            <li><a href="#">{{ tag }}</a></li>
          {% endfor %}
        </ul>
      </div>
    </div>
  </div>
{% endfor %}

<div class="item item-no-border">
  <div class="decoration" style="background-image: url('media/artwork/thum/8-3-6.jpg')"></div>
  <div class="literature">
    <h3>PRIDE & PREJUDICE</h3>
    <div class="">
      <h5>May 01, 2018</h5>
      <div class="hash-tags">
        <span>#self#green#potrait</span>
      </div>
    </div>
  </div>
</div>
<div class="item">
  <div class="decoration" style="background-image: url('media/artwork/thum/T4.jpg')"></div>
  <div class="literature">
    <h3>PRIDE & PREJUDICE</h3>
    <div class="">
      <h5>May 01, 2018</h5>
      <div class="hash-tags">
        <span>#self#green#potrait</span>
      </div>
    </div>
  </div>
</div>
<div class="item item-no-border">
  <div class="decoration" style="background-image: url('media/artwork/thum/8-3-5.jpg')"></div>
  <div class="literature">
    <h3>PRIDE & PREJUDICE</h3>
    <div class="">
      <h5>May 01, 2018</h5>
      <div class="hash-tags">
        <span>#self#green#potrait</span>
      </div>
    </div>
  </div>
</div>
<div class="item item-no-border">
  <div class="decoration" style="background-image: url('media/artwork/thum/8-3-4.jpg')"></div>
  <div class="literature">
    <h3>PRIDE & PREJUDICE</h3>
    <div class="">
      <h5>May 01, 2018</h5>
      <div class="hash-tags">
        <span>#self#green#potrait</span>
      </div>
    </div>
  </div>
</div>
<div class="item item-no-border">
  <div class="decoration" style="background-image: url('media/artwork/thum/8-3-3-HUY.jpg')"></div>
  <div class="literature">
    <h3>PRIDE & PREJUDICE</h3>
    <div class="">
      <h5>May 01, 2018</h5>
      <div class="hash-tags">
        <span>#self#green#potrait</span>
      </div>
    </div>
  </div>
</div>
<div class="item">
  <div class="decoration" style="background-image: url('media/artwork/thum/8-3-1.jpg')"></div>
  <div class="literature">
    <h3>PRIDE & PREJUDICE</h3>
    <div class="">
      <h5>May 01, 2018</h5>
      <div class="hash-tags">
        <span>#self#green#potrait</span>
      </div>
    </div>
  </div>
</div>
<div class="item item-no-border">
  <div class="decoration" style="background-image: url('media/artwork/thum/8-3-2.jpg')"></div>
  <div class="literature">
    <h3>PRIDE & PREJUDICE</h3>
    <div class="">
      <h5>May 01, 2018</h5>
      <div class="hash-tags">
        <span>#self#green#potrait</span>
      </div>
    </div>
  </div>
</div>
<div class="item item-no-border">
  <div class="decoration decoration-h" style="background-image: url('media/artwork/thum/T2.jpg')"></div>
  <div class="literature">
    <h3>PRIDE & PREJUDICE</h3>
    <div class="">
      <h5>May 01, 2018</h5>
      <div class="hash-tags">
        <span>#self#green#potrait</span>
      </div>
    </div>
  </div>
</div>
<div class="item"></div>
<div class="item"></div>
<div class="item"></div>
