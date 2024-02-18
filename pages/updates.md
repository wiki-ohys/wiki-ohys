---
layout: content
title: Site Updates and News
---
<center><h2>{{ page.title }}</h2></center>

***
{% for update in site.data.updates %}
<div class="updates-date-heading">{{ update.date }}</div>
{{ update.info | markdownify | remove: "<p>" | remove: "</p>" }}
{% if update.url %}
<a href="{% link {{ update.url }} %}">Link</a>
{% endif %}
{% endfor %}
