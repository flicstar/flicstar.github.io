---
layout: page
title: Editing
featured_image: 

---


<div class="outer">
  <div class="post-feed-title inner">Writing about editing</div>
       <div class="post-feed inner-wide">
       {% for post in site.categories.editing %}
         {% include postbox.html %}
    {% if post.url %}
       <a href="{{ post.url }}">{{ post.title }}</a>
         {{ post.excerpt }}
    {% endif %}
  {% endfor %}         
    </div>   
</div>
