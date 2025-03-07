---
layout: default
title: Blog
featured_image: 

---

<div class="featured-posts outer">
<div class="outer">
  <div class="post-feed-title inner">Tech writing, editing, open source, work I'm doing, and things I find interesting</div>
       <div class="post-feed inner-wide">
       {% for post in site.categories.blog %}
         {% include postbox.html %}
  {% endfor %}         
    </div>   
</div>
</div>
