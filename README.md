# index.md

---
layout: home
---

Welcome to My Portfolio!

## About Me

Write a brief introduction about yourself here. Good.

## Projects

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})
{{ project.description }}
{% endfor %}

# _layouts/home.html

---
layout: default
---

<h1>{{ page.title }}</h1>
<p>{{ site.description }}</p>

{{ content }}
