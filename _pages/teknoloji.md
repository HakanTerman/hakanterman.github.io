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
  <ul><h3 class="post-title">
    <li><a href="{{ post.url }}">{{ post.title }} - {{ post.date | date: "%d/%m/%Y" }}</a></li>
  </h3></ul>
  </div>
  {% endif %}
  {% endfor %}
</div>
