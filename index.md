---
layout: default
title: A Sociologist in the World
tagline: Research and thoughts from a Sociologist working in the 'real world'
---
**About the Site:** _A Sociologist in the World_ catalogues my social science research and writing since finishing grad school. I will also use the site to explore new research topics, methodologies, and socio-economic events as I build my skill-set. I'll likely focus on topics of professional interest to me: labor and employment; social, economic, and demographic changes in the world; and diving into data. But I might also detour into science fiction, history, or the odd pop culture reverie.

**About me:** I have a PhD in Sociology from the [State University of New York at Albany](http://www.albany.edu/sociology/). I've spent my post-grad school years working outside academia: a non-profit research organization, [a federal statistical agency](https://census.gov/), [a consulting company](https://www.summitllc.us/), and most recently in tech. My research passion is employment: labor markets, occupations, organization of work, you name it. But I also have a fascination with the Greek and Roman empires, due to my undergrad years at [St. John's College](https://www.sjc.edu/).

##Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
