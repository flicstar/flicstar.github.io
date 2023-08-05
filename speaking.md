---
layout: page
title: Speaking Posts

----

<p>Posts in category "Writing" are:</p>

<ul>
  {% for post in site.categories.speaking %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
