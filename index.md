---
layout: home
---

# Basics
<ol>
{% for item in site.basics %}
  <li>
    <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>

  </li>
{% endfor %}
</ol>

# Gestalt
<ol>
{% for item in site.gestalt %}
  <li>
    <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>

  </li>
{% endfor %}
</ol>

# Layout
<ol>
{% for item in site.layout %}
  <li>
    <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>

  </li>
{% endfor %}
</ol>

# Typography
<ol>
{% for item in site.typography %}
  <li>
    <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>

  </li>
{% endfor %}
</ol>

# Color
<ol>
{% for item in site.color %}
  <li>
    <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>

  </li>
{% endfor %}
</ol>
