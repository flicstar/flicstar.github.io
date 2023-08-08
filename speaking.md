---
layout: default
title: Speaking Posts
featured_image: 

---

<div class="featured-posts outer">
  <img src="/assets/images/pages/typo3logo.png" alt="TYPO3 logo" align="right"/>
<div class="outer">  
  <div class="post-feed-title inner"></div>
       <div class="post-feed inner-wide">
       {% for post in site.categories.speaking %}
         {% include postbox.html %}
  {% endfor %}         
    </div>   
</div>
</div>
