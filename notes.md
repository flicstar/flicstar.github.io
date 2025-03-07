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
          <article class="note-full">
        <div class="note-meta">
            <time class="note-date" datetime="{{ note.date | date: '%Y-%m-%d' }}" rel="bookmark">
                {{ note.date | date: "%B %-d, %Y" }}
            </time>
        </div>
        <div class="note-content">
            {{ note.content }}
        </div>
        <hr class="note-divider">
    </article>
  {% endfor %}         
    </div>   
</div>
</div>