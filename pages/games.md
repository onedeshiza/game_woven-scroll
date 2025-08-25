---
layout: default
title: "フリーゲーム一覧"
permalink: /pages/games/
---

<p><h2>フリーゲーム一覧</h2></p>

<br>

只今準備中です。  
暫しお待ちください。  

<ul>
  {% for post in site.categories.free-games %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>