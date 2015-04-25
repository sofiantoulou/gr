---
layout: page
show_meta: false
title: "Style your content!"
subheadline: "Layouts"
header:
   image_fullwidth: ""
permalink: "/design/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
