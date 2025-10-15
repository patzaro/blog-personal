---
title: Cómo crear enlaces a otras entradas en el blog
description: Proceso para enlazar entre posts.
date: 2025-07-17
tags: ["links", "eleventy"]
---

Para crear un enlace entre entradas del blog, puedes usar una etiqueta Markdown como esta:

```
[Lee también este otro post](../firstpost.md)
```
Pongo dos puntos ".." porque está en otro directorio. VSCodium me ayuda en esto y me da todos los posibles objetivos.

que produce este enlace:

[Lee también este otro post](../firstpost.md)

Este enlace lleva al archivo firstpost.md, suponiendo que esté ubicado en la misma carpeta que tu post actual (content/blog/).

> *Nota: también se pueden usar permalinks que mola más.*
