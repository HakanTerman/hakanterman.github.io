---
permalink: /teknoloji/
title: "Teknoloji Blogu"
excerpt: "Teknoloji Blogu - Hakan TERMAN"
layout: single
header:
  image: /assets/images/teknoloji.jpg
  caption: "Fotoğraf Sahibi : [Andrea Obzerova](https://500px.com/ABOPhotography)"
---

<div class="posts">
  {% for post in site.posts %}

    {% assign author = site.authors[post.author] %}
    {{ author.display_name }}

  {% if post.category == 'Teknoloji' %}
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
