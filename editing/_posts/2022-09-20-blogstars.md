---
layout: default
title: "Blogstars"
summary: I review articles written by tech bloggers and call out things they've done well.
tags: [ editing, tech-writing ]
image: 
featured_image_thumbnail: https://cdn.hashnode.com/res/hashnode/image/upload/v1663657105269/hijIuBomg.png
featured_image: 
---

Blogstars is a series where I review articles written by tech bloggers and call out things they've done well, to help other bloggers improve their writing. 


> G'day! flicstar your friendly editor here. I help writers create great written content. Let me help you improve your writing by taking a look at what some others are doing really well.


I like making writers feel good 🤗 In this series, I do a [Positivity Pass](https://openstrategypartners.com/blog/the-positivity-pass-and-why-we-do-it/) and use [editing codes](https://github.com/open-strategy-partners/editing-codes) to review articles and call out specific techniques for effective writing.



<div class="featured-posts outer">
<div class="outer">
  <div class="post-feed-title inner"></div>
       <div class="post-feed inner-wide">
       {% for post in site.categories.blogstars %}
         {% include postbox.html %}
  {% endfor %}         
    </div>   
</div>
</div>


