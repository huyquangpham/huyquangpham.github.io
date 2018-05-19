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
