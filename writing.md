---
layout: default
title: Writing
featured_image: 

---



<div class="featured-posts outer">
<p>I write about technical writing, open source, work I'm doing, and things I find interesting.</p>
<div class="outer">
  <div class="post-feed-title inner">Writing about writing</div>
       <div class="post-feed inner-wide">
       {% for post in site.categories.writing %}
         {% include postbox.html %}
  {% endfor %}         
    </div>   
</div>
</div>
