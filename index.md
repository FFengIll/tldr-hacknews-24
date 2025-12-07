---
layout: default
title: "TLDR.HackNews24"
permalink: "/"
---

# TLDR.HackNews24

As the title said, read it 1000 years later bro.

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.date | date_to_string }}</p>
    </li>
  {% endfor %}
</ul>
