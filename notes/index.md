---
layout: page
title: Activities & Notes
---
{% for page in site.posts %}
  {% if post.categories contains 'Notes' %}
    <div class="item">
      <h3><a href="/uni/{{ post.url }}">
        {{ post.title }}
      </a></h3>


<p>{{post.description}}</p>  
    </div>


  {% endif %}
{% endfor %}
