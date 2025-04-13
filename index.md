---
layout: default

title: Home

---

## Welcome to Daniel's Recipe Book

Browse my collection of family-friendly, high-protein, and meal-prep-friendly recipes below:

{% for recipe in site.recipes %}

- [{{ recipe.title }}]({{ recipe.url }})

{% endfor %}
