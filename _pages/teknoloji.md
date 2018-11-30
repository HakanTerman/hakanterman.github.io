---
permalink: /teknoloji/
title: "Teknoloji Blogu"
excerpt: "Teknoloji Blogu - Hakan TERMAN"
layout: single
header:
  image: /assets/images/CVHakan.jpg
  caption: "Fotoğraf Sahibi : [Jozef Polc](https://500px.com/halfpoint)"
---

<div class="posts">
  {% for post in site.posts %}

    {% assign author = site.authors[post.author] %}
    {{ author.display_name }}

  {% if post.category == 'Teknoloji' %}
  <div class="post">
  <ul><h3 class="post-title">
    <li><a href="{{ post.url }}">{{ post.title }} - {{ post.date | date_to_string }}</a></li>
  </h3></ul>
  </div>
  {% endif %}
  {% endfor %}
</div>
