---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Tutorials

<ul>
    {% for tutorial in site.data.tutorials %}
    <li><a href="{{ tutorial.path | relative_url }}">{{ tutorial.name }}</a></li>
    {% endfor %}
</ul>