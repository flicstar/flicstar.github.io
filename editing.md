---
layout: page
title: Editing
featured_image: 

---

<div class="post-feed inner-wide">

  {% for post in site.categories.editing %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% include postbox.html %}
  {% endif %}
  {% endfor %}

</div>

