---
layout: default
title: A Sociologist in the World
tagline: Research and thoughts from a Sociologist working in the 'real world'
---
<h2 style="color:#191970;">About the Site</h2> 
_A Sociologist in the World_ catalogues my social science research and writing since finishing grad school. I will also use the site to explore new research topics, methodologies, and socio-economic events as I build my skill-set. I'll likely focus on topics of professional interest to me: labor and employment; social, economic, and demographic changes in the world; and diving into data. But I might also detour into science fiction, history, or the odd pop culture reverie.

<h2 style="color:#191970;">Recent Posts</h2>

{% for post in site.posts %}
<div>
  <a href="{{ post.url }}"><h5>{{ post.title }}</h5></a>
  <a href="{{ post.url }}"><img class="left" src="{{ post.thumbnail }}"></a>
  {{post.excerpt}}
</div>
{% endfor %}


