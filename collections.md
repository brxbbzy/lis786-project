---
title: Collections
layout: page
permalink: /collections
---
## Here you can view the art collections by Cameron Alagna

# Digital Pieces

{% for piece in site.pieces %}
{% if piece.category == 'digital' %}
<h3>{{ piece.title }}</h3>
<p><img src="{{ piece.image }}" alt="alt text..."</p>
<p>{{ piece.content }}</p>
<p>Category: {{ piece.category }}</p>
{% endif %}
{% endfor %}