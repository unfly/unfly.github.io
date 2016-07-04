---
layout: page
title: PROJECTS
permalink: /projects/
---

项目展示
<article class="container">
  <ul class="row list-unstyled">
    {% for post in site.posts %}
    <li class="col-md-4">
      <a href="{{ post.url }}">
        <p>{{ post.excerpt }}</p>
        <p>{{ post.title }}</p>
        </a>
    </li>
    {% endfor %}
  </ul>
</article>
