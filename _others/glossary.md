---
title: Glossary
author: Bilal MAJJAD
date: 2024-09-17
category: Jekyll
layout: post
---

{% for entry in 
site.data.glossary %}
- [**{{ entry.term }}**]({{entry.url}}){:target="_blank"} : {{entry.definition}}
{% endfor %}
