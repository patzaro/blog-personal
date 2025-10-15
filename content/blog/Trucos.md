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


### This is a very long heading that I want to wrap This is a very long heading that I want to wrap This is a very long heading that I want to wrap This is a very long heading that I want to wrap

Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.

```js
// this is a command
function myCommand() {
	let counter = 0;
	counter++;
}

// Test with a line break above this line.
console.log('Test');
```

### Heading with a [link](#code)

Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.

```
// this is a command
function myCommand() {
	let counter = 0;
	counter++;
}

// Test with a line break above this line.
console.log('Test');
```

## Section Header

Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the loop on focusing solely on the bottom line.
