---
title: Collections
layout: page
permalink: /Collections
---

Here you can view the art collections by Cameron Alagna

{% for machine in site.pieces %}
{% if pieces.category == 'digital' %}
<h3>{{ piece.title }}</h3>
<p> <img src="{{ piece.image }}" alt="alt text..."</p>
<p>{{ piece.content }}</p>
<p>Category: {{ piece.category }}</p>
{% endif %}
{% endfor %}