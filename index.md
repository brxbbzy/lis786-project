---
title: Home
layout: page
permalink: /home
teeth_url: https://i.ibb.co/ZR9YHmb/art11.jpg
tears_url: https://i.ibb.co/q0n1MLd/Art13.jpg
sketch_url: https://i.ibb.co/HzwQZ7W/Art8.jpg
image_alt: image of recent work from facebook 
---

## Bajo el Mismo Sol 
# View the recent works created by **Cameron Alagna**. 

{% for piece in site.pieces %}
<h3>{{ piece.title }}</h3>
<p> <img src="{{ piece.image }}" alt="alt text..." /> </p>
<p>{{ piece.content }}</p>
<p>Category: {{ piece.category }}</p>
{% endfor %}


<div class="content-left" markdown="1">
This is some sample content infomation to view how the divs work.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Pellentesque id nibh tortor id aliquet lectus proin. Fusce id velit ut tortor pretium viverra. Tristique senectus et netus et malesuada fames ac. Sed turpis tincidunt id aliquet risus feugiat. Aenean vel elit scelerisque mauris pellentesque. Feugiat sed lectus vestibulum mattis ullamcorper velit. Quis commodo odio aenean sed adipiscing diam donec adipiscing tristique. Nulla facilisi cras fermentum odio eu feugiat. Tristique nulla aliquet enim tortor at auctor urna. Sit amet nulla facilisi morbi tempus. Vel turpis nunc eget lorem dolor sed. Gravida dictum fusce ut placerat orci nulla pellentesque dignissim enim. Eu feugiat pretium nibh ipsum consequat nisl vel pretium lectus. Netus et malesuada fames ac turpis egestas.
</div>

<div class= "img-right" markdown="1">
![image of recent work from facebook](https://i.ibb.co/HzwQZ7W/Art8.jpg)
</div>

<div class="clearfix"></div>