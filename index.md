---
layout: default
title: Home
---

## Welcome to Daniel's Recipe Book

Browse my collection of family-friendly, high-protein, and meal-prep-friendly recipes below:

<ul>
  {% for recipe in site.recipes %}
    <li><a href="{{ recipe.url }}">{{ recipe.title }}</a></li>
  {% endfor %}
</ul>  

<h3>Debug Output</h3>
<pre>
{{ site.recipes | jsonify }}
</pre>