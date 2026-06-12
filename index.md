---
layout: home
title: SEのテック＆仮想通貨メモ
---

# 投稿一覧
{% for post in site.posts %}
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%Y-%m-%d" }}</p>
{% endfor %}
