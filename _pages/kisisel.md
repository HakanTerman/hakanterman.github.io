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
  <ul><h3 class="post-title">
    <li><a href="{{ post.url }}">{{ post.title }} - {{ post.date | date: "%d/%m/%Y" }}</a></li>
  </h3></ul>
  </div>
  {% endif %}
  {% endfor %}
</div>
