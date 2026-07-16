---
title: Blog
---
This is a demo Jekyll blog, it contains nothing but nonsense 🙂

<ul>
  {% for post in site.posts %}
    <li>
      <strong>{{ post.date | date_to_string }}:</strong> <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>