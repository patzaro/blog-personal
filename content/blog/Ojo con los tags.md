---
title: Ojo con los tags
description: This is a post on My Blog about tags.
date: 2025-07-18
tags: 
 - tags
 - obsidian
---

## Los tags pueden causar problemas en Netlify

Los tags son muy delicados para Netlify, son causa frecuente de fallos. Deben llevar el siguiente formato:

```
tags: 
 - blanco
 - azul
```
Si no, Netlify puede dar error al hacer Deploy. Y además, así es como los pone Obsidian.

Pero también lo entiende así:

```
tags: ["un tag", "otro tag"]
```

Aunque parece que llega con ponerlos separados por comas.

## Capitalización de las iniciales

Si pongo un tag `caca` en minúsculas, Netlify le cambia la primera letra a mayúscula: `Caca`. Y si pongo `digital-garden` lo cambia por `Digital-Garden`.
