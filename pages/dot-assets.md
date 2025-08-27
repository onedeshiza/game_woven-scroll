---
layout: default
title: "ドット絵素材一覧"
permalink: /pages/dot-assets/
---

<p><h1>ドット絵素材一覧</h1></p>

<br>

当座にて製作したドット絵素材です。  
完全自作素材、<b>他者様の改変素材</b>等があります。  
利用規約を御一読の上、DL・御利用ください。  
  
<a href="{{ site.baseurl }}/pages/LICENSE/">御利用規約</a>

<h1>これはh1</h1>
<h2>これはh2</h2>
<h3>これはh3</h3>

<br>

<ul>
  {% for post in site.categories.dot-assets %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
