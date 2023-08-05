---

layout: page
title: Editing
featured_image: 

---

<p>Posts in category "Editing" are:</p>

<ul>
  {% for post in site.categories.editing %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>


