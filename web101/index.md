---
layout: page
title: WEB Communications
categories: [WEB101]
---
{% for page in site.pages %}
  {% if page.categories contains 'WEB101' %}
    <div class="item">
      <h3>{{page.title}}</h3>
      <p>{{page.description}}</p>  
    </div>
  {% endif %}
{% endfor %}
