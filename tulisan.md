---
layout: page
title: 'Daftar Artikel'
permalink: /tulisan/
---

{% assign id_posts = site.posts | where: "lang", "id" %}
{% for post in id_posts %}

- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %B %Y" }}
  {% endfor %}
