---
layout: default
---
<ul>
  {% for post in site.posts %}
    <li>
      <!-- <a href="{{ post.url | relative_url }}"> -->
      {{ post.content }}
      <!-- </a> -->
    </li>
  {% endfor %}
</ul>