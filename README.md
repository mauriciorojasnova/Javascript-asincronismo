# Javascript y Asincronismo

## ¿Qué es Asincronismo?

JavaScript es un lenguaje asíncrono, es decir, que se puede aprovechar el tiempo ejecutando tareas que pueden tardar más y al mismo tiempo ejecutar tareas breves. Un ejemplo de esto sucede con las llamadas a APIs, las cuales se ejecutan de manera asíncrona si se usan los métodos adecuados que pueden ser los callbacks, promesas o asyn/await.

## Ventajas y desventajas

Los distintos métodos usados para crear el asincronismo presentan ventajas y desventajas, las cuales son:

Los callbacks son fáciles de implementar y son universales, es decir, corren en cualquier navegador. Sin embargo, al anidar muchos elementos la comprensión del código se torna difícil. Esto se conoce como 'callback hell'.

Las promesas son fácil de enlazar para obtener más llamadas, lo cual supera la desventaja de los callbacks. Sin embargo, no maneja excepciones sino sólo un catch al final. Requiere un polyfill para que funcione en navegadores antiguos.

Async y await es el método más fácil de comprender debido a su sencilla sintaxis. Sin embargo, el tiempo de espera puede ser largo. También necesita de un polyfill para que funcione en navegadores antiguos.

Nota: Toda la información fue tomada de el [Curso de Asincronismo con Javascript](https://platzi.com/cursos/asincronismo-js/) de Platzi.




