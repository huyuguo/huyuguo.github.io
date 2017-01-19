---
layout: default
title: 我的博客
---

<h2>{{page.title}}</h2>
<p>最新文章</p>
<ul>
    {% for post in site.posts %}
        <li>{{post.date | date_to_string("Y-m-d")}} <a href="{{site.baseurl}}{{post.url}}">{{post.title}}</a></li>
    {% endfor %}
</ul>


[Link to another page](another-page).