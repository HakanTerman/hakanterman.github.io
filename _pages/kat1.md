---
permalink: /kat1.html
title: "kat1"
excerpt: "Hakan TERMAN - Özgeçmiş - CV"
layout: single
modified: 2018-11-29T20:53:07.573882-04:00
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
