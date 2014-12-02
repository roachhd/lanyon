---
layout: page
title: WEB Communications
categories: [WEB101]
---
site.categories.CATEGORY

{% for post in site.categories.WEB101 %}
    <li>{{ post.title }}</li>
{% endfor %}


<div class="posts">
  {% for page in site.categories.WEB101 %}
  <div class="post">
    <h1 class="post-title">
      <a href="/uni/{{ page.url }}">
        {{ post.title }}
      </a>
    </h1>

    {{ page.content }}
  </div>
  {% endfor %}
</div>
