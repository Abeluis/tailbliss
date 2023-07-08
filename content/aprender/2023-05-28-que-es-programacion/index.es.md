---
title: 1. ¿Qué es la programación?
author: Abel Luis Muñoz Vera
date: '2023-05-28'
slug: [que-es-la-programacion]
categories:
  - aprende-r
tags:
  - Programacion
  - R
  - Rstudio
featured_image:  
description: ''
editor_options: 
  markdown: 
    wrap: sentence
---

# Introducción

![](/curso_files/Banner_1.png)

Antes de comenzar, me gustaría tratar algunos temas sobre programación que considero claves de entender desde un principio porque la programación es un proceso de aprendizaje constante.
Se necesitan curvas de aprendizaje que sean apropiadas para el nivel de conocimiento en el que nos encontramos, partiendo desde lo más básico que es entender qué es en realidad la programación.

## Desmitificando la programación

Me hubiera gustaría decirlo con mis propias palabras, pero Al Sweigart[^1] lo explica de forma excelente en las siguientes palabras.

[^1]: Libro Automate the Boring Stuff with Python (2015) disponible para su lectura en línea en el siguiente enlace \> [Libro digital](https://automatetheboringstuff.com/#toc)

Los programas de televisión y las películas suelen mostrar a programadores tecleando furiosamente secuencias crípticas de 1s y 0s en pantallas brillantes, pero la programación moderna no es tan misteriosa.
**Programar no es más que introducir instrucciones para que el ordenador las ejecute**.
Estas instrucciones pueden calcular números, modificar texto, buscar información en archivos o comunicarse con otros ordenadores a través de Internet.
Todos los programas utilizan instrucciones básicas como bloques de construcción.
Instrucciones más comunes:

-   "Haz esto; luego haz aquello".

-   "Si esta condición es cierta, realiza esta acción; si no, haz aquella".

-   "Haz esta acción tal número de veces".

-   "Sigue haciéndolo hasta que se cumpla esta condición".

La programación no parece tan complicada una vez que entendemos que consiste en dar instrucciones a nuestro computador para que las ejecute.
Pero estas instrucciones deben estar en un lenguaje que nuestro computador entienda.

## El lenguaje

Generalmente al discutir sobre la evolución de los humanos[^2] se le da especial importancia al desarrollo del lenguaje.
Si bien existen diversas teorías sobre su origen así como características diferenciadoras con el lenguaje de otros animales, es la capacidad de hablar sobre ficciones la característica más especial del lenguaje que hablan los humanos.
En este sentido, la ficción es lo que es ajeno a la realidad como la invención del mito y el uso de expresiones y figuras literarias que son imposibles en la realidad.

[^2]: Sapiens.
    De animales a dioses, Yuval Noah Harari (2016) disponible para su lectura en el siguente enlace \> [BPDigital](https://www.bpdigital.cl/opac?id=00364785)

El lenguaje de programación es también esa ficción, ese intangible que solo se materializa cuando ejecutamos el código con una sintaxis y semántica que nuestro computador debe entender.

## Lenguaje de programación

Un lenguaje de programación consiste en una gramática específica (similar a un lenguaje hablado por los seres humanos) que define los comandos y la lógica que debe aplicar el sistema en cuestión bajo unos parámetros específicos[^3].

[^3]: Python a fondo: domine el lenguaje del presente y del futuro.
    Óscar Ramírez Jiménez (2021).
    Disponible para su lectura en el siguiente enlace \> [BPDigital](https://www.bpdigital.cl/opac?id=00342858)

### Niveles

El nivel determina a grandes rasgos las funciones que tiene un lenguaje y como programadores aficionados e incluso para programadores profesionales, la mayoría del tiempo utilizaremos solo lenguajes de alto nivel.

**Niveles de lenguajes de programación**

| Nivel      | Características                                                                                                                                                                                                                                                                                                                                                                                                                 |
|-----------|-------------------------------------------------------------|
| Bajo nivel | Proporciona poca o ninguna abstracción del hardware de un sistema informático. Está diseñado para representar fielmente la arquitectura y funcionalidad del hardware como el procesador, la memoria y los dispositivos de entrada/salida. Los lenguajes de bajo nivel suelen utilizarse para tareas que requieren un control directo sobre el hardware, como la programación de sistemas o el desarrollo de sistemas embebidos. |
| Alto nivel | Proporciona un mayor nivel de abstracción del hardware de un sistema informático en comparación con los lenguajes de bajo nivel. Está diseñado para ser más legible y permite a los programadores escribir código más cercano al lenguaje natural, lo que facilita su comprensión, escritura y mantenimiento.                                                                                                                   |

Fuente: Texto generado gracias a ChatGPT[^4]

[^4]: ChatGPT, respuesta a "¿Qué es un lenguaje de bajo nivel? y ¿Qué es un lenguaje de alto nivel" 3 de junio de 2023, Recuperado del siguiente enlace \> [OpenAI](https://chat.openai.com)

Los lenguajes de alto nivel más populares actualmente son Python, Java, C, C++, Javascript, entre otros, R es también un lenguaje de alto nivel aunque no tan popular en áreas que no sean el análisis y visualización de datos junto a la investigación en general.

### Características

Existen muchísimos lenguajes de programación, estos tienen características que los hacen apropiados para ciertas tareas y de la preferencia de algunos programadores.
En se enumeran las siguientes elementos principales de un lenguaje de programación.

**Elementos principales**

| Elemento                        | Descripción                                                                                                                       |
|-----------------|-------------------------------------------------------|
| Sintaxis                        | Las reglas específicas y la estructura utilizadas para escribir código en un lenguaje de programación.                            |
| Tipos de datos                  | El tipo de valores que pueden almacenarse en un programa, como números, cadenas y booleanos.                                      |
| Variables                       | Ubicaciones de memoria con nombre que pueden almacenar valores.                                                                   |
| Operadores                      | Símbolos utilizados para realizar operaciones con valores, como sumas, restas y comparaciones.                                    |
| Estructuras de control          | Sentencias utilizadas para controlar el flujo de un programa, como las sentencias if-else, los bucles y las llamadas a funciones. |
| Bibliotecas y marcos de trabajo | Colecciones de código preescrito que pueden utilizarse para realizar tareas comunes y acelerar el desarrollo.                     |
| Paradigmas                      | Estilo o filosofía de programación utilizado en el lenguaje, como procedimental, orientado a objetos o funcional.                 |

Fuente: Geeks for Geeks[^5]

[^5]: GeeksforGeeks, Introduction to Programming Languages (2023).
    Recuperado del siguiente enlace \> [GeekforGeeks](https://www.geeksforgeeks.org/introduction-to-programming-languages/)

# Notas
