---
layout: content
title: Site Updates and News
---
<center><h2>.:: {{ page.title }} ::.</h2></center>

***
{% for update in site.data.updates %}
<div class="updates-date-heading">{{ update.date }}</div>
<p style="padding-left: 1em;">{{ update.info }}</p>
{% if update.url %}
<p style="text-indent: 2em;"><a href="{% link {{ update.url }} %}">Link</a></p>
{% endif %}
{% endfor %}
