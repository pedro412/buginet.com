---
title: 'Crea tu primer sitio estático con Hugo'
date: 2019-06-23T20:48:08-05:00
draft: false
description: 'Aprende lo básico y crea tu primer sitio web con este veloz ⚡ framework'
---

En este tutorial aprenderás lo básico de HUGO, ¿Qué es y para que nos sirve?, además te iré guiando paso a paso para que crees tu primer sitio desde cero sin tener conocimientos avanzados en Go(lenguaje de programación).  

## Requisitos  

Para seguir esta guía no es necesario que tengas conocimientos en HTML, CSS y/o JavaScript, pero si ya conoces un poco de estas tecnologías te puede resultar más fácil.

## Sitios estáticos vs dinámicos
----------------------

### Sitios estáticos

Para entender mejor por que usar HUGO primero hablemos de lo que son los sitios estáticos, los sitios Estáticos son aquellos en los que no existe una lógica de servidor de tras de ellos, son prácticamente puro HTML, CSS y a veces JavaScript, estos sitios son muy usados para proyectos como blogs, sitios de noticias, documentación en donde no se requiere programar ni agregar funcionalidades complejas como un login y pagos por ejemplo.

Las principales ventajas de este tipo de sitios son:

- Son fáciles de crear y mantener.
- Como no requiere un backend ni base de datos ni nada por el estilo son baratos de hostear o alojar ya que el servidor solo va a estar sirviendo archivos estáticos.
- Al solo servir archivos estáticos, los sitios de este tipo son muy veloces a comparación de los sitios dinámicos.
- Están optimizados para SEO por su naturaleza.   

### Sitios dinámicos

Los sitios dinámicos son aquellos en los que existe una lógica de programación de tras de ellos, un ejemplo fácil de entender seria Facebook, cada que entramos a Facebook vemos algo diferente tu y yo, ya que al servidor primero le llega quien eres y con base a eso busca que te debe mostrar lógicamente te muestra cosas relacionadas con tus amigos, esto se genera en el servidor y finalmente te es servido.

Las principales ventajas de este tipo de sitios son:

- Puedes hacer prácticamente cualquier cosa que se te ocurra, desde una red social, hasta un editor de texto o imagen en línea.
 

## ¿Qué es HUGO SSG?
----------------------

> Hugo es un moderno y veloz generador de sitios estáticos escrito en Go, y diseñado para que la creación de sitios vuelva a ser divertida.

Hugo SSG por sus siglas en ingles Static Site Generator, generador de sitios estáticos es un framework el cual nos da las herramientas necesarias para crear un sitio de este tipo sin la necesidad de volver a inventar la rueda, nos ayuda a crear de una forma estructurada y elegante nuestra página, siguiendo estándares y buenas practicas, así como Hugo existen otros generadores de sitios estáticos tales como Jekyll y Gatsby por mencionar algunos.


