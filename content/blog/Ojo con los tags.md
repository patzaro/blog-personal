---
title: Ojo con los tags
description: This is a post on My Blog about tags.
date: 2025-07-18
tags: 
 - tags
 - azul
---

Los tags son muy delicados para Netlify, son causa frecuente de fallos. Deben llevar el siguiente formato:

```
tags: ["un tag", "otro tag"]
```

Si no, Netlify da error al hacer Deploy.

Pero también lo entiende así, y además, así es como los pone Obsidian:

```
tags: 
 - blanco
 - azul
```

Si pongo un tag `caca` en minúsculas, Metlify le cambia la primera letra a mayúscula: `Caca`.

