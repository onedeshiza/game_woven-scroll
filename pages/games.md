---
layout: default
title: "フリーゲーム一覧"
permalink: /pages/games/
---

<ul>
  {% for post in site.categories.free-games %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>