---
title: 'Como funciona JavaScript'
description: 'Lenguaje de alto nivel, multiparadigma, de un solo hilo, interpretado, dinámico...'
date: 2019-07-03T23:40:07-05:00
draft: false
type: 'Articulos'
---

## Alto nivel

Cuando ejecutamos un programa de JavaScript ya sea en el navegador o en nuestra computadora con Node, se necesita reservar memoria en la RAM para guardar cosas como objetos y variables que hayas referenciado en tu código, además se necesita un hilo de tu CPU para poder ejecutar las instrucciones que especificaste pero tu como desarrollador nunca te preocupas de estas cosas ya que JavaScript lo hace todo por ti, es por esto que es un lenguaje de Alto nivel ósea que tiene abstracciones.

## Interpretador y compilador

Se podría decir que JavaScript es un lenguaje interpretado, esto significa que nuestro código no es leído directamente por nuestra computadora primero tiene que leerlo el interpretador y este le dice que hacer a la computadora.

Existen también lenguajes compilados como Java o C en donde el código es analizado y compilado antes de poder ejecutarse, esta compilación traduce el código escrito y lo pasa a código binario el cual nuestras computadoras pueden entender y ejecutar.

## Dinamismo

Cuando decimos que un lenguaje de programación es dinámico es por que no tenemos que especificar que tipo de datos estamos usando ya sea numérico o de caracteres, a diferencia de los lenguajes estáticos como Java en donde si se tiene que especificar en el momento de declarar un variable de que tipo es por ejemplo si creamos una variable numérica tenemos que especificar que se trata de una variable numérica. Los lenguajes de alto nivel por lo general son dinámicos como Python y JavaScript.

## Multiparadigma

La mayoría de lenguajes de programación de uso general son multiparadigmas ósea que puedes escribir código orientado a objetos(OOP) o funcional y mezclarlos como tu gustes.

## Basado en prototipos

Una de las cosas raras de JavaScript es que esta basado en herencia de prototipos por ahora no te preocupes por esto en otro articulo estaré explicando a detalle de que se trata solo ten en mente que todo lo que escribimos en JavaScript son objetos y cada uno de estos objetos esta ligado a su prototipo y esto crea una cadena de prototipos en donde los objetos pueden heredar comportamiento de otros objetos.

## Recapitulando

Sabemos que JavaScript es un lenguaje de alto nivel interpretado dinámico basado en prototipos y multiparadigma. Pero también tenemos que sabe que es un lenguaje de un solo hilo que administra la memoria en automático que no bloquea la ejecución y que tiene un Event Loop que se compila en ejecución o JIT compilated. 

ECMA International solo define que es de alto nivel interpretado dinámico basado en prototipos y multiparadigma pero nunca específica lo de un solo hilo que administra la memoria en automático que no bloquea la ejecución y que tiene un Event Loop que se compila en ejecución entonces quien decide esto.

Los detalles de implementación comentados anteriormente quedan a cargo de los motores de los navegadores que interpretan JavaScript. Lo motores más populares son SpiderMonkey de Mozilla y V8 de Google ambos tienen algo llamado JIT o Just in Time Compilation, en el caso de V8 compilara todo el código a código de maquina antes de ejecutarlo a diferencia de un interpretador en donde se interpretarían las instrucciones una por una en tiempo de ejecución esto le da a V8 una velocidad significativa.

JavaScript solo puede hacer una cosa a la vez, cuando ejecutamos un código de JavaScript se alojan dos regiones en memoria el call stack y el heap. El call stack esta diseñado para ser una region de uso continuo de alto rendimiento usado para ejecutar tus funciones. Heap un albergue de memoria sin estructura en donde se almacenan cosas como objetos.

JavaScript es un lenguaje que no se bloquea por que siempre esta escuchando que funciones se ejecutan aunque sea de un solo hilo, así que nunca esta esperando a que una función se termine de ejecutar para poder correr otras funciones.

