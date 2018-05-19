<aside class="l-side">
  <section class="me-box">
    <a id="me" class="me" href="http://huyquangpham.com"></a>
    <h4>HUY PHẠM</h4>
  </section>
  <section class="collections">
    <label class="btn btn-tran toggle-collections" for="p-toggle-collections">...</label>
    <input checked type="checkbox" id="p-toggle-collections" name="p-toggle-collections" />
    <div class="container container-collection">
      <h5 class="legend">Charactering</h5>
      {% for post in site.posts | sort_by: "date" %}
        {% if post.categories contains "charactering" %}
          <a href="{{ post.url | absolute_url }}" class="">{{ post.title }}</a>
        {% endif %}
      {% endfor %}

      <h5 class="legend">Animals</h5>
      {% for post in site.posts | sort_by: "date" %}
        {% if post.categories contains "animals" %}
          <a href="{{ post.url | absolute_url }}" class="">{{ post.title }}</a>
        {% endif %}
      {% endfor %}

      <h5 class="legend">Cards</h5>
      {% for post in site.posts | sort_by: "date" %}
        {% if post.categories contains "cards" %}
          <a href="{{ post.url | absolute_url }}" class="">{{ post.title }}</a>
        {% endif %}
      {% endfor %}

      <h5 class="legend">Childrens</h5>
      {% for post in site.posts | sort_by: "date" %}
        {% if post.categories contains "childrens" %}
          <a href="{{ post.url | absolute_url }}" class="">{{ post.title }}</a>
        {% endif %}
      {% endfor %}
    </div>
  </section>
</aside>
