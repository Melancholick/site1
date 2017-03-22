---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

## Remote jobs for:

[Developers](/devs/)

[QA engineers](/qas/)

[DevOps and Sysadmins](/admins/)

[Designers (todo)]
    
## Sample Posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



