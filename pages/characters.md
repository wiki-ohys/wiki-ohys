---
layout: content
title: List of Characters
---
## {{ page.title }}

---
<strong>First Generation</strong>

<ul class="list">
  {% for page in site.pages %}
    {% if page.path contains '/characters/first' %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>


<strong>Second Generation</strong>

<ul class="list">
  {% for page in site.pages %}
    {% if page.path contains '/characters/second' %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

<strong>Third Generation</strong>
<ul class="list">
  {% for page in site.pages %}
    {% if page.path contains '/characters/third' %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
<strong>Fourth Generation</strong>
<ul class="list">
  {% for page in site.pages %}
    {% if page.path contains '/characters/fourth' %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

<strong>Fifth Generation</strong>
<ul class="list">
  {% for page in site.pages %}
    {% if page.path contains '/characters/fifth' %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
<strong>Sixth Generation</strong>

<ul class="list">
  {% for page in site.pages %}
    {% if page.path contains '/characters/sixth' %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

<strong>Seventh Generation</strong>
<ul class="list">
  {% for page in site.pages %}
    {% if page.path contains '/characters/seventh' %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}</ul>

<strong>Other Characters</strong>
<ul class="list">
  {% for page in site.pages %}
    {% if page.path contains '/characters/misc' %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
---
## Family Tree
<!-- <figure> -->
<img src="/assets/chars.png" width="90%">
<figcaption><a href="/assets/chars.png">Enlarge Image</a></figcaption>
<!-- </figure> -->