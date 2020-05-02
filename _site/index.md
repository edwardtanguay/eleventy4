---
title: The First Page
date: Created
layout: base
tags: 
    - home
    - flashcards
    - info
    - other
---

## {{ title }}

**Publish Date:** {{ page.date }}

New index.md page:

<ul>
{% for item in tags %}
<li>{{ item | safe }}</li>
{% endfor %}
</ul>