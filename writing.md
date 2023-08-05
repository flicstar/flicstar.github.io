---

layout: page
title: Writing Posts
----


<ul>
  {% for post in site.categories.writing %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a>
         {{ post.excerpt }}
        </li>
    {% endif %}
  {% endfor %}
</ul>