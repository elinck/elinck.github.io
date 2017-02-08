---
layout: archive
permalink: /news/
Title: "Latest news"
author_profile: true
header: 
  image: banner3.jpg
---

This page is currently under construction as I work on switching over my blog to a static site. In the mean time, you can visit its old home, [over at Wordpress](https://beyondtheranges.wordpress.com/)


<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>