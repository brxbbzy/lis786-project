---
title: Home
layout: page
permalink: /home
teeth_url: https://i.ibb.co/ZR9YHmb/art11.jpg
tears_url: https://i.ibb.co/q0n1MLd/Art13.jpg
sketch_url: https://i.ibb.co/HzwQZ7W/Art8.jpg
image_alt: image of recent work from facebook 
---
# Bajo el Mismo Sol 
## View the recent works created by **Cameron Alagna**. 

{% include page-teeth.html %}
{% include page-tears.html %}
{% include page-sketch.html %}

{% for piece in site.pieces %}
<!-- Do Something -->
   
    <h3>{{ piece.title }}</h3>

    <p> <img src="{{ piece.image }}" alt="alt text..."</p>
    <p>{{ piece.content }}</p>
    <p>Category: {{ piece.category }}</p>
    <p> </p>

{% endfor %}

<!-- ![image of recent work from facebook]({{ page.teeth_url }}) -->