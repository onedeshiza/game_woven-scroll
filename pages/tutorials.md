---
layout: default
title: "ウディタ講座一覧"
permalink: /pages/tutorials/
---

<p><h1>ウディタ講座一覧</h1></p>

<br>

完全初心者に向け、簡単なコモンイベントの製作方法を紹介しております。  
<br>
<br>
<ul>
  {% for post in site.categories.tutorials %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
