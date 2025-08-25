---
layout: default
title: "ウディタ講座 一覧"
---

「WOLF RPGエディター」、通称「ウディタ」にて、コモンイベントを作成するための記事です。  
初心者～中級者向けの記事となっておりますので、お役立てください。  
  
<hr>
  
<ul>
  {% for post in site.categories.tutorials %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small> – {{ post.excerpt | strip_html | truncate: 100 }}
    </li>
  {% endfor %}
</ul>
