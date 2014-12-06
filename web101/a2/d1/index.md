---
layout: subpage
title: A2 D1
description: "Essay"
categories: 
tags: [WEB101, Assignment 2]
---

###### My First Draft

This is a word test count. I have typed 12 words here.


**Draft One** *max 1500 words*.


---

{% capture words %}
  {{ page.content | number_of_words | strip_html | minus: 90 }}
{% endcapture %}
{% unless words contains "-" %}
  {{ words | strip_html | plus: 0 | append: " words" }}
{% endunless %}

{% capture words %}
  {{ page.content | number_of_words | strip_html | minus: 5 }}
{% endcapture %}
{% unless words contains "-" %}
  {{ words | strip_html | plus: 5 | divided_by: 180 | append: " minute read" }}
{% endunless %}

