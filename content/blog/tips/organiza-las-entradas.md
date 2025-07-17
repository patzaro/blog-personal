---
title: Organiza las entradas en GitHub
description: This is a post on My Blog about agile frameworks.
date: 2025-07-17
tags:
  - GitHub
  - Posts
---

## ¿Afecta en algo tener las entradas en diferentes carpetas en el repositorio de Github?

Tener las entradas del blog en diferentes carpetas no afecta en absoluto el funcionamiento del sitio cuando se usa Eleventy en GitHub Pages. Eleventy procesa todos los archivos dentro de `content/blog/`, incluidos los que estén en subcarpetas, siempre y cuando estén configurados correctamente.

Puedo tener todas las entradas en la misma carpeta, pero si empiezo a tener muchas entradas, será mejor organizarlas. Por ejemplo:

```
content/blog/
├── uno/
│   └── entrada1.md
├── dos/
│   └── entrada2.md
└── general/
    └── entrada3.md
```

etc

## Cosas a tener en cuenta

En la web no se diferencian en nada esas entradas. Solo hay que tener cuidao al poner enlaces entre páginas, hay que indicar la referencia a la carpeta correcta. Asegúrate de usar rutas correctas (../, /, etc.) al enlazar desde una entrada a otra.


