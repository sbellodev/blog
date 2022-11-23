---
title: Santi Bello Blog
name: 'blog-usando-vue-nuxt-markdown'

year: 1 Enero 2019
color: '#8e7964'
trans: 'blog-using-vue-nuxt-markdown'
id: 'vue-nuxt-blog'
description: |
  Prueba.
---





## Prueba?

Prueba [JAMStack](https://jamstack.org/), está construido para obtener contenido mediante APIs, por ello muchas personas utilizan headless CMSs como [Contentful](https://www.contentful.com/) 

**Por .**

### Importación de los artículos en la página principal dependiendo del idioma

Mediante la función asíncrona `asyncData` que proporciona Nuxt solo en sus páginas (no en sus componentes) hago una importación de los Markdown que tengo guardados en la carpeta `content` del proyecto. Posteriormente los devuelvo en forma de promesa como un array de objetos. Como puedes ver a continuación, la importación depende de la constante `blogs` que será el array `blogsEs` o `blogsEn` dependiendo del idioma de la página.

```javascript
Prueba codigo js
```


### Generación de páginas dinámicas a partir de archivos Markdown

<image-responsive
    imageURL="blog/vue-nuxt-blog/performance.jpg"
    :width="'952'"
    :height="'509'"
    alt="performance" />
