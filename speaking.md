---
layout: page
title: Speaking Posts
----

<ul>
  {% for post in site.categories.speaking %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a>
         {{ post.excerpt }}
        </li>
    {% endif %}
  {% endfor %}
</ul>

