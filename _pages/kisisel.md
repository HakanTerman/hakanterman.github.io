---
permalink: /kisisel/
title: "Kişisel Blog"
excerpt: "Kişisel Blog - Hakan TERMAN"
layout: single
header:
  image: /assets/images/kisisel.jpg
  caption: "Fotoğraf Sahibi : [David Charouz](https://500px.com/DavidCharouz)"
---

<div class="posts">
  {% for post in site.posts %}

    {% assign author = site.authors[post.author] %}
    {{ author.display_name }}

  {% if post.category == 'Kisisel' %}
  <div class="post">
  <div class="post-inner">
  <div class="date">{{ post.date | date: "%d/%m/%Y" }}</div>
  <div class="title">
<a href="{{ post.url }}">{{ post.title }}</a>
  </div>
  </div>  
  </div>
  {% endif %}
  {% endfor %}
</div>
