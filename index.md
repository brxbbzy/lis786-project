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

### This is some sample content infomation to view how the divs work. ###

</div>

<div class= "img-right" markdown="1">
![image of recent work from facebook](https://i.ibb.co/HzwQZ7W/Art8.jpg)
</div>
<div class="clearfix"></div>