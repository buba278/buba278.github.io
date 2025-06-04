--- 
layout: default 
title: archive notes
--- 
<div class="page-content-wrapper"> <h1>All Notes</h1> <ul> {% for post in site.posts %} <li> <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - <span style="color: #777; font-size: 1em;">{{ post.date | date: "%Y.%m.%d" }}</span> </li> {% endfor %} </ul> </div>