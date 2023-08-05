---
layout: page
title: Writing Posts

----

<p>Posts in category "Writing" are:</p>

<ul>
  {% for post in site.categories.writing %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
