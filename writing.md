---

layout: page
title: Writing Posts
----

<p>Posts in category "Writing" are:</p>

<div id="archives">
{% for category in site.categories.writing %}
  <div class="archive-group">
    {% capture writing %}{{ category | first }}{% endcapture %}
    <div id="#{{ writinge | slugize }}"></div>
    <p></p>

    <h3 class="category-head">{{ writing }}</h3>
    <a name="{{ writing | slugize }}"></a>
    {% for post in site.categories[writing] %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
    </article>
    {% endfor %}
  </div>
{% endfor %}
</div>
