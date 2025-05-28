---
layout: default
title: Líder en Modo Debug
description: Historias, decisiones y aprendizajes de un líder entre tecnología, producto y negocio.
---
# Líder en Modo Debug

Este no es un blog de frases motivacionales.
Tampoco es un manual de metodologías perfectas.
Es un espacio real, escrito por alguien que **lidera, ejecuta y aprende** en medio de la entropía.

Acá vas a encontrar:

- Historias de producto que no estaban en el pitch.
- Decisiones difíciles, liderazgos imperfectos, roadmaps que cambian.
- Aprendizajes reales desde el lado tech, el lado negocio y el lado humano.

Si alguna vez tuviste que explicar por qué una feature no salió a tiempo, este blog es para vos.

**Bienvenid@ al modo debug del liderazgo.**

## Sobre mí

Soy Rodrigo, uso remera negra casi todos los días y aprendí que liderar tecnología, producto y negocio no se trata de tener todas las respuestas, sino de saber hacer buenas preguntas en medio del caos.

Tengo un MBA, casi 20 años de experiencia entre startups, corporativos, pitchs que salieron mal y productos que salieron bien. Fui CTO, director de producto, ingeniero, y cofundador. Hoy lidero equipos que construyen cosas reales y trato de evitar el PowerPoint vacío.

**Escribo para los que ejecutan. Los que aprenden. Los que lideran con dudas y aún así, avanzan.**



## Últimas publicaciones

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br/>
      <small>{{ post.date | date: "%d %b %Y" }}</small>
    </li>
  {% endfor %}
</ul>
