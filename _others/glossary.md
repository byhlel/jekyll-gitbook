---
title: Glossary
author: Bilal MAJJAD
date: 2024-09-17
category: Jekyll
layout: post
---



{% assign sorted_entries = site.data.glossary | sort_natural: 'term' %}

{% for entry in 
sorted_entries %}
- [**{{ entry.term }}**]({{entry.url}}){:target="_blank"} : {{entry.definition}}
{% endfor %}
