---
layout: default
title: Hem
---

# Välkommen till Demokratiska partiet, De Nya Svenskarna (DPNS)

## Senaste inlägg

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
---

[Follow us on Instagram](https://www.instagram.com/multireligionval/){:target="_blank"}
<hr>
<div align="center" style="margin-top: 40px; padding: 20px; font-family: sans-serif;">
  <p>© 2026 Multi Religion Val. All rights reserved.</p>
  <a href="https://www.instagram.com/multireligionval/" target="_blank" rel="noopener noreferrer" style="text-decoration: none; color: #E1306C; font-weight: bold;">
    📷 Instagram: @multireligionval
  </a>
</div>
