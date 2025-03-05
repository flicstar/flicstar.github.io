---
layout: default
title: Notes
featured_image: 
---

<div class="featured-posts outer">
<div class="outer">
  <div class="post-feed-title inner">Notes are shorter posts</div>
       <div class="post-feed inner-wide">
       {% for note in site.categories.notes %}
         {% include notebox.html %}
  {% endfor %}         
    </div>   
</div>
</div>