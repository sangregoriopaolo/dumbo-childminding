---
layout: page
title: Gallery
permalink: /gallery
---

{% for file in site.static_files %}
{{ file.path }}
{% endfor %}

{% include image-gallery.html folder="/gallery/painting" %}
