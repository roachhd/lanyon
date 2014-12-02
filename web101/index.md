---
layout: page
title: WEB Communications
categories: [WEB101]
---
site.categories.CATEGORY

<div class="posts">
  {% for post in site.categories.WEB101 %}
  <div class="post">
    <h1 class="post-title">
      <a href="/uni/{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>


    <span class="post-date">{{ post.date | date_to_string }}</span>


    {{ post.content }}
  </div>
  {% endfor %}
</div>
