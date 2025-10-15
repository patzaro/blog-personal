---
title: Trucos para Eleventy y Netlify
description: This is a post on My Blog about win-win survival strategies.
date: 2025-10-15
tags: ["trucos", "eleventy"]
---


## Enlaces

- Insertar un enlace:

`[link](url)`

## Problemas con los tags: mejor ponerlos en minúsculas

El problema es que tienes dos tags, "Netlify" (con mayúscula) y
  "netlify" (con minúscula), en las publicaciones de tu blog. Eleventy,
  el generador de sitios que probablemente estás usando, crea una página
   para cada etiqueta. Sin embargo, al generar la URL para estas
  páginas, convierte ambos tags a "netlify", lo que provoca un
  conflicto porque intenta crear dos páginas con la misma dirección.

## Títulos de las entradas

El título de la entrada es el que ponga la propiedad `title`. El nombre del fichero puede ser otro.

## Enlaces a otros posts del blog

Se puede ver como crearlos [en esta entrada](./trucos-eleventy/Como-enlazar-posts.md)


## Para qué sirve la propiedad "description" en el frontmatter

Esta descripción suele ser utilizada para:

- Mejorar el SEO (Search Engine Optimization), ya que los motores de búsqueda pueden mostrarla en sus resultados como texto resumen de la página.

- Mostrarse en las etiquetas meta HTML <meta name="description" content="..."> para ofrecer una vista previa del contenido cuando se comparte el enlace en redes sociales u otras plataformas.

- Proporcionar un texto resumen que puede ser mostrado en listados, índices o tarjetas dentro del sitio web.

La propiedad _description_ no tiene un efecto automático en Eleventy hasta que la plantilla o layout la usa expresamente para generar etiquetas meta o contenido visual.

### Heading with a [link](#code)

Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.


