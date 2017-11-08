---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
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

# Color
<ol>
{% for item in site.color %}
  <li>
    <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
    
  </li>
{% endfor %}
</ol>
