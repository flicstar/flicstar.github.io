---
layout: page
title: Editing
featured_image: 

---


<ul>
  {% for post in site.categories.editing %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a>
         {{ post.excerpt }}
        </li>
    {% endif %}
  {% endfor %}
</ul>
