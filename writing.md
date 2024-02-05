---
layout: default
title: Writing
featured_image: 

---

<p><img src="/assets/images/typo3bookcover.jpg" alt="TYPO3 Book Cover" hspace="20" /> <img src="/assets/images/twpbookcover.jpg" alt="TWP Book Cover" hspace="20" /> </p>

<div class="featured-posts outer">
<div class="outer">
  <div class="post-feed-title inner">Writing about writing, open source, work I'm doing, and things I find interesting</div>
       <div class="post-feed inner-wide">
       {% for post in site.categories.writing %}
         {% include postbox.html %}
  {% endfor %}         
    </div>   
</div>
</div>
