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
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%d/%m/%Y" }}
  </li>
{% endfor %}
</ul>
