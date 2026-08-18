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
<p class="empty-note">Nothing here yet, first post shows up whenever I actually finish something from <a href="/roadmap/">this list</a>. Come watch the mess happen live (on <a href="https://www.twitch.tv/basitbalogun10">Twitch</a>.. and <a href="https://www.youtube.com/@basitbalogun10">YT</a>) in the meantime.</p>
{% endif %}
