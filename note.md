---
layout: default
title: Note
description: "A collection of my shorter, informal thoughts and updates."
permalink: /note/
---

<div class="featured-posts outer">
<div class="outer">
  <div class="post-feed-title inner">Notes are shorter posts</div>
       <div class="post-feed inner-wide">
       {% for note in site.categories.notes %}
         {% include postbox.html post=note %}
       {% endfor %}         
    </div>   
</div>
</div>