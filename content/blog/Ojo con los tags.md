---
title: Ojo con los tags
description: This is a post on My Blog about tags.
date: 2025-07-18
tags: 
---

Los tags son delicados para Netlify, deben llevar el siguiente formato:

```
tags: ["un tag", "otro tag"]
```

Si no, Netlify da error al hacer Deploy.

Pero, si es un solo tag, no poner corchetes ni comillas:

```
tags: another
```
