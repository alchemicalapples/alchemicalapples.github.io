---
layout: page
title: Games
permalink: /games/
---
{% for item in site.games %}
  <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
  <p>{{ item.description }}</p>
  <div><a href="{{ item.url }}"><img src="{{ item.thumbnail }}"></a></div>
{% endfor %}
