---
layout: page
title: Heygate
permalink: /heygatepages/
---
<h1>The Heygate estate redevelopment</h1>
{% for heygatepage in site.heygatepages %}
<a class="post-link" href="{{ heygatepage.url | relative_url }}">
            {{ heygatepage.name | escape }}
          </a>
  <img src="{{ heygatepage.image | escape }}" width="75%" style="border:5px solid #000000; padding:3px; margin:5px">
  
{% endfor %}
