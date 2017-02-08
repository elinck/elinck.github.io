---
layout: archive
permalink: /news/
Title: "Latest news"
author_profile: true
header: 
  image: banner3.jpg
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>