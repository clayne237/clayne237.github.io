---
layout: default
title: A Sociologist in the World
tagline: Research and thoughts from a Sociologist working in the 'real world'
---
## About the Site 
_A Sociologist in the World_ catalogues my social science research and writing since finishing grad school. I will also use the site to explore new research topics, methodologies, and socio-economic events as I build my skill-set. I'll likely focus on topics of professional interest to me: labor and employment; social, economic, and demographic changes in the world; and diving into data. But I might also detour into science fiction, history, or the odd pop culture reverie.

## Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}"><img src="{{ post.thumbnail }}"/>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{post.excerpt}}
    </li>
  {% endfor %}
</ul>

