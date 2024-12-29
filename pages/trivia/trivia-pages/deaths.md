---
layout: trivia
title: Deaths in OHYS
description: There are incredible lives and incredible deaths as well. This is all about the deaths.
permalink: /trivia-death/
---

{% assign sorted_pages = site.pages | where_exp: "page", "page.path contains 'trivia-details/deaths'" | sort: "path" %}

<ul>
{% for page in sorted_pages %}
    <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>
