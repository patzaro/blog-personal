---
title: Ojo con los tags
description: This is a post on My Blog about tags.
date: 2025-07-18
tags: 
 - Netlify
---

Los tags son muy delicados para Netlify, son causa frecuente de fallos. Deben llevar el siguiente formato:

```
tags: ["un tag", "otro tag"]
```

Si no, Netlify da error al hacer Deploy.

Pero, si es un solo tag, no poner corchetes ni comillas:

```
tags: another tag
```
