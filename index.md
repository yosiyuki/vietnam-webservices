---
layout: page
title: ベトナム・ウェブ調査
tagline: ベトナムでベトナム人のウェブを調査しています。
---
{% include JB/setup %}

# 最新のエントリ

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
