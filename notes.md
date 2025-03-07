---
layout: default
title: Notes
featured_image: 

---

<div class="featured-posts outer">
<div class="outer">  
  <div class="post-feed-title inner">Short notes and quick thoughts</div>
       <div class="post-feed inner-wide">
      {% for post in site.categories.notes %}
         {% include notebox.html %}
         {% unless forloop.last %}
           <hr class="note-separator">
         {% endunless %}
  {% endfor %}         
    </div>   
</div>
</div>
