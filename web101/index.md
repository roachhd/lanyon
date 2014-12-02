---
layout: page
title: WEB Communications
categories: [WEB101]
---
site.categories.CATEGORY
{% for post in site.categories[category_name] %}
    <li>{{ post.title }}</li>
{% endfor %}


<div class="posts">
  {% for page in site.categories.WEB101 %}
  <div class="post">
    <h1 class="post-title">
      <a href="/uni/{{ page.url }}">
        {{ page.title }}
      </a>
    </h1>


    <span class="post-date">{{ post.date | date_to_string }}</span>


    {{ post.content }}
  </div>
  {% endfor %}
</div>
