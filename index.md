---
layout: default
title: Home
---

# Benvenuti sul mio blog!
Ciao, questo è il mio primo sito ospitato su **GitHub Pages**.

### Cosa troverai qui:
* Articoli tecnici
* Riflessioni personali
* Progetti futuri

## I miei articoli
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
