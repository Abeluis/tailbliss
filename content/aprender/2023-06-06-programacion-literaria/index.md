---
title: 2. La necesidad de la programación letrada
date: '2023-06-06'
draft: false
language: es
featured_image: ../assets/images/pana/documento.png
summary: Lenguaje claro e instrucciones detalladas. 
description: Lenguaje claro e instrucciones detalladas. 
author: Abel Luis Muñoz Vera
authorimage: ../assets/images/global/author.webp
categories: aprende-r
tags:
  - Programacion
  - Rmarkdown
---

# Introducción

En la capsula anterior exploramos conceptos y definiciones en torno a la programación, reiterando una idea central es que *programar no es más que introducir instrucciones para que el ordenador las ejecute* y estas instrucciones son realizadas en un lenguaje de programación que nuestro computador entienda. Pero si no sabemos de programación o si intentamos aprender, ante la falta de una explicación clara de lo que hacen tales instrucciones, estas no tendrán ningún significado y generalmente serán incomprensibles para nosotros.

# Programación letrada

Donald E. Knuth a través de su trabajo en áreas relacionadas a las ciencias de la computación junto a la publicación de su extensa obra en "El arte de la programación", se ha convertido en uno de los padres de la informática moderna. Para Knuth[^1] la programación debe seguir un orden lógico que se asemeja más al racionamiento humano y sugiere que los programadores deben

[^1]: Donald Knuth. "Literate Programming (1984)" en Computer Journal disponible el siguiente enlace \> [Literateprogramming](http://www.literateprogramming.com/knuthweb.pdf)

> En lugar de imaginar que nuestra tarea principal es instruir a un ordenador sobre lo que debe hacer, concentrémonos más bien en explicar a los humanos lo que queremos que haga el ordenador.

En torno a esta idea los programas suelen incorporar instrucciones que explican el paso a paso junto a documentación más detallada de las opciones y posibilidades de ese programa pudiendo ser un documento "LEEME", texto incorporado al código fuente como comentarios, párrafos y capítulos o verdaderos libros. Pero independiente del formato y nivel de complejidad el proceso de programación letrada o literaria tiene al menos tres etapas[^2]:

[^2]: Etapas propuestas por Yihui Xie en Dynamic Documents with R and knitr. Libro disponible en en el siguiente enlace \> [GitHub](https://duhi23.github.io/Analisis-de-datos/Yihue.pdf)

1.  Analizar el documento fuente y separar el código de las narraciones

2.  Ejecutar el código fuente y obtener resultados

3.  Mezclar los resultados del código fuente con las narraciones originales

# Ejemplo

Quizás puede seguir resultado algo un tanto alejado sin un ejemplo, por lo que, vamos a realizar una simple demostración con uno de los programas más simples: **Hello World** a través del lenguaje R.


```r
# ------------------------- INTRODUCCION ------------------------- ####
# Hello World sirve como un ejercicio práctico en la introducción de 
# un lenguaje de programación, no es necesario que tengas instalado R
# tu computador.
# ------------------------- FUNCION print() ---------------------- ####
# En simple, la función print() imprime el contenido dentro del paréntesis
# ------------------------- Clase character ---------------------- ####
# En simple, la clase character son textos y se ponen con comillas '' o ""
print("Hello World")
```

```
## [1] "Hello World"
```

Como puedes ver, dentro del primer bloque de código de entrada se explicó lo que se realiza con lineas que inician con un símbolo gato \# y también con algunas divisiones dentro del mismo código. Mientras que el segundo bloque de salida imprimió "Hello World". Todo esto para códigos más complejos se vuelve sumamente útil y necesario.

# Conclusión

Por mi formación académica que está más ligada al área jurídica y de ciencias sociales, la programación letrada cobra especial sentido por la atención al detalle que debe tener la palabra escrita dentro del código para que pueda ser entendido y aprendido. Recurro nuevamente a las palabras de Knuth porque considero que es clave para aprender y que debe de ser una costumbre que adquiramos, en primer lugar para tomar apuntes y no olvidar cosas importantes de lo que estamos aprendiendo, en segundo lugar para que los que programemos sea comprensible para otros.

> El profesional de la programación literaria puede considerarse un ensayista, cuya principal preocupación es la exposición y la excelencia del estilo. Con el diccionario de sinónimos en la mano, elige cuidadosamente los nombres de las variables y explica qué significa cada una de ellas. Se esfuerza por conseguir un programa comprensible porque sus conceptos se han introducido en el orden más adecuado para la comprensión humana, utilizando una mezcla de métodos formales e informales que se refuerzan mutuamente.

# Notas
