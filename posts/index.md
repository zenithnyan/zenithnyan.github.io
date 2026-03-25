---
layout: default
title: New Text
---

# Posts

![Banner](https://capsule-render.vercel.app/api?type=Waving&color=timeGradient&height=300&animation=fadeIn&section=header&text=Archive&fontSize=100)

New Text

<ul>
  {% for post in site.blog %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<br />
<br />
<div align="left">
<a class="left" href="/">← Previous</a>
</div>

<a onclick="topFunction()" id="btn-to-top"><i class="fa-solid fa-caret-up"></i></a> 
