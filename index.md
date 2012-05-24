---
layout : page
---
```#!/usr/bin/ruby``` 


<div style="float:left;margin:0 10px 10px 0" markdown="1">
    ![Ruby Logo](./images/Ruby.png)
</div>

<div class="blog-index">
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
</div>


Older Posts.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

