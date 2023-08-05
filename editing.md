---
layout: page
title: Editing
featured_image: 

---


<div class="outer">
  <div class="post-feed-title inner">Writing about editing</div>
    {% endif %}
       <div class="post-feed inner-wide">
       {% for post in site.categories.editing %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a>
         {{ post.excerpt }}
        </li>
    {% endif %}
  {% endfor %}         
    </div>   
</div>
