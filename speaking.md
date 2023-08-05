---
layout: page
title: Speaking Posts
featured_image: 
----

<ul>
  {% for post in site.categories.speaking %}
    {% if post.url %}
        <li>{{post.date}}<a href="{{ post.url }}">{{ post.title }}</a> 
         {{ post.excerpt }}
        </li>
    {% endif %}
  {% endfor %}
</ul>
