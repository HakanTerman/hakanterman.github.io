---
permalink: /kategori/teknoloji/
title: "Teknoloji"
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
    <h1 class="post-title">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h1>
    {{ post.content }}
  </div>
  {% endif %}
  {% endfor %}
</div>
