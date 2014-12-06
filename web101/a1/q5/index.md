---
layout: subpage
title: A1 Q5.
description: "What is RSS and why is it significant to Web 2.0?"
categories: [WEB101]
tags: [WEB11, Assignment 1, question 5]
---

###### What is RSS and why is it significant to Web 2.0?
This is a word test count. I have typed 12 words here.


**Draft One** *max 150 words*.


---

{% capture words %}
  {{ page.content | number_of_words | strip_html | minus: 98 }}
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
