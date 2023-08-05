---
layout: page
title: Editing
featured_image: 

---
<div class="outer">
<div class="post-feed inner-wide">
<ul>
  {% for post in site.categories.editing %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% include postbox.html %}
  {% endfor %}
</ul>
</div>
</div>

<!-- Pagination-->
{% include pagination.html %}
