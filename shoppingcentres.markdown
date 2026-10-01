---
layout: page
title: Shopping Centre/UAL
permalink: /shoppingcentres/
---
<h1>E&C shopping centre redevelopment</h1>
{% for shoppingcentre in site.shoppingcentres %}
<a class="post-link" href="{{ shoppingcentre.url | relative_url }}">
            {{ shoppingcentre.name | escape }} 
          </a>
          {{ shoppingcentre.description }}
          <img src="{{ shoppingcentre.image | escape }}" width="75%" style="border:5px solid #000000; padding:3px; margin:5px">
  
  
{% endfor %}