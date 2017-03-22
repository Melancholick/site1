---
title: Remote Jobs for QA's
permalink: qas
layout: page
---


{% for jobad in site.data.expqaremote %}
<h3>{{ jobad.title }}</h3>

{{ jobad.sourceName }} - {{ jobad.published }}<br>
Tags:{% for tag in  jobad.tags %}  {{ tag }};{% endfor %}<br>

{{ jobad.content }}

{% endfor %}

