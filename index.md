---
layout: home
title: SEのテック＆仮想通貨メモ
---

# ブログへようこそ
エンジニア視点での技術メモと投資情報を発信中。

## 投稿一覧
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
  </li>
{% endfor %}
</ul>
