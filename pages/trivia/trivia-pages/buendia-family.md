---
layout: trivia
title: Buendia Family Trivia
description: All the nail-biting, shockingly minute details about the family.
permalink: /bfamily/
---

{% assign sorted_pages = site.pages | where_exp: "page", "page.path contains 'trivia-details/buendia-family'" | sort: "path" %}

<ul>
{% for page in sorted_pages %}
    <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>