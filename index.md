---
layout: default
title: Inicio
---

## Bienvenido a mi blog de prácticas

A continuación se muestran los artículos publicados por los alumnos:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%d/%m/%Y" }}
    </li>
  {% endfor %}
</ul>
