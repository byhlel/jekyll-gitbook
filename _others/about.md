---
title: Glossary
author: Bilal MAJJAD
date: 2024-09-17
category: Jekyll
layout: post
---

{% for entry in 
site.data.glossary %}
- [**{{ entry.term }}**][{{entry.url}}] : {{entry.definition}}
{% endfor %}

[Github Pages][1] without generating and uploading HTML bundle every time when there are
changes to the original repository.

[1]: https://pages.github.com