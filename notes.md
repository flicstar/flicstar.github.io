---
layout: default
title: Notes
featured_image: 

---

<div class="featured-posts outer">
<div class="outer">  
  <div class="post-feed-title inner">A collection of shorter thoughts and updates</div>
       <div class="post-feed inner-wide">
      {% for post in site.categories.notes %}
         {% include notebox.html %}
  {% endfor %}         
    </div>   
</div>
</div>
