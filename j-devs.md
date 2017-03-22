---
title: Remote Jobs for developers/software engineers
permalink: devs
layout: page
---


{% for jobad in site.data.expdevremote %}
<h3>{{ jobad.title }}</h3>

{{ jobad.sourceName }} - {{ jobad.published }}<br>
Tags:{% for tag in  jobad.tags %}  {{ tag }};{% endfor %}<br>

{{ jobad.content }}

{% endfor %}

