---
layout: default
title: Posts
nav_order: 2
---

# 📝 Blog Entries

Welcome! Here you'll find posts on survey design, measurement techniques, and other user research topics.

## Posts

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <br>
    <small>{{ post.date | date: "%B %d, %Y" }}</small>
  </li>
  {% endfor %}
</ul>
