---
layout: subpage
title: WEB101 A1 Q1.
description: "What is the Internet?"
categories: [WEB101]
tags: [WEB11, Assignment 1]
---

###### What is the Internet?

**Draft One** *max 15 words*.

{% capture words %}
  {{ page.content | number_of_words | minus: 250 }}
{% endcapture %}
{% unless words contains "-" %}
  {{ words | plus: 250 | append: " words" }}
{% endunless %}

{% capture words %}
  {{ page.content | number_of_words | minus: 250 }}
{% endcapture %}
{% unless words contains "-" %}
  {{ words | plus: 250 | divided_by: 180 | append: " minute read" }}
{% endunless %}
