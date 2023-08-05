---
layout: page
title: Speaking Posts
featured_image: 

---

<ul>
  {% for post in site.categories.speaking %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a> {{ post.date | date: '%Y-%m-%d' }}
         {{ post.excerpt }}
        </li>
    {% endif %}
  {% endfor %}
</ul>
