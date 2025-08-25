---
layout: default
title: "ドット絵素材一覧"
permalink: /pages/dot-assets/
---

<p><h2>ドット絵素材一覧</h2></p>
<br>
当座にて製作したドット絵素材です。  
完全自作素材、他者様の改変素材等があります。  
利用規約を御一読の上、DL・御利用ください。  
  
<a href="{{ site.baseurl }}/pages/LICENSE/">御利用規約</a>

<br>

<ul>
  {% for post in site.categories.dot-assets %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>