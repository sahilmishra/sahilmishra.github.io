---
layout: page
title: "blog"
permalink: /blog
by: sahil mishra
---

<link rel="stylesheet" href="assets/css/style.css" >
<div class="wrapper">
    <ul>
      {% for post in site.posts %}
        <li>
          <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
      {% endfor %}
    </ul>
</div>
