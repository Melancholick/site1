---
title: Remote Jobs for DevOps and Sysadmins
permalink: admins
layout: page
---


{% for jobad in site.data.expadminremote %}
<h3>{{ jobad.title }}</h3>

{{ jobad.sourceName }} - {{ jobad.published }}<br>
Tags:{% for tag in  jobad.tags %}  {{ tag }};{% endfor %}<br>

{{ jobad.content }}

{% endfor %}

