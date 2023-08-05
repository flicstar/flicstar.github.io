---
layout: page
title: Writing Posts
featured_image: 
----

<p>I write about technical writing, open source, work I'm doing, and things I find interesting.</p>

<ul>
  {% for post in site.categories.writing %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a>
         {{ post.excerpt }}
        </li>
    {% endif %}
  {% endfor %}
</ul>
