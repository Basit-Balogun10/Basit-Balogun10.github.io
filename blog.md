---
title: Blog
permalink: /blog/
---

# Blog

Write-ups whenever something's actually finished — what I built, what broke, what I got wrong along the way.

{% if site.posts.size > 0 %}
{% for post in site.posts %}
<div class="post-list-item">
  <span class="date">{{ post.date | date: "%B %-d, %Y" }}</span>
  <a href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}
{% else %}
<p class="empty-note">Nothing here yet, first post shows up whenever I actually finish something lol. Come watch the mess happen live in the meantime.</p>
{% endif %}
