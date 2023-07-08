---
title: 3. El lenguaje de programación R
date: '2023-06-10'
author: Abel Luis Muñoz Vera
language: es
featured_image: ../assets/images/aprender/codigo.png
summary: Breve explicación e instrucciones para instalarlo.
description: Breve explicación e instrucciones para instalarlo.
authorimage: ../assets/images/global/author.webp
categories: aprende-r
tags:
  - Programacion
  - Lenguaje R
---

Hola, te recomiendo revisar previamente la cápsula anterior [¿Qué es la programación?](https://abeluis.netlify.app/aprender/2023-05-28-que-es-programacion/) ya que en esta cápsula se aplicaran algunas elementos previamente explicados allí.

# Introducción

Como ha sido señalado anteriormente, programar no es más que introducir instrucciones para que el ordenador las ejecute mediante un lenguaje de programación. Existen diversos lenguajes, pero esta sección se centra en el lenguaje de programación R y la interfaz de desarrollo RStudio.\
R es un sistema de cálculo estadístico y gráficos. Consta de un lenguaje más un entorno de ejecución con gráficos, un depurador, acceso a determinadas funciones del sistema y la posibilidad de ejecutar programas almacenados en archivos de script[^1]. Cuenta con otras características, pero es importante destacar que es un software libre distribuido bajo un copyleft al estilo GNU, y parte oficial del proyecto GNU ("GNU S").

[^1]: R-Project, What is R? (2023). Recuperado del siguiente enlace \> [CRANR-Project](https://cran.r-project.org/index.html)

Este tipo de software bajo esta licencia tiene una comunidad que promueve la libertad de uso, modificación y distribución del software y también buscar protegerlo frente a la privatización que empresas y personas puedan intentar realizar con el software. Luego de varias décadas de trabajo, existe una comunidad consolidad que crea y desarrolla funcionalidades que por lo general son completamente gratuitas, existiendo documentación y acceso a estas herramientas para utilizarlas. Esto supone una ventaja enorme frente a otros programas y lenguajes de programación destinados al análisis de datos ya que por ejemplo, STATA y SPSS son de pago y tienen una comunidad y soporte mucho más pequeña.

## Descargar de R

La instalación se realiza instalando R desde la página oficial en [The R Project for Statistical Computing](https://www.r-project.org/).

![](images/Screenshot1.png)

La versión actual es la 4.3.1 lanza el 23 de junio de 2023 y que tiene como nombre clave Beagle Scouts, la descarga se puede realizar en el [CRAN](https://cran.r-project.org/mirrors.html), acrónimo de Comprehensive R Archive Network.

El mirror en Chile es sostenido por el Departamento de Ciencias de la Computación, Universidad de Chile que dispone el siguiente enlace \> [cran.dcc.uchile.cl](https://cran.dcc.uchile.cl/)

![](images/Screenshot2-01.png)

Podrás descargar los archivos necesarios para su instalación en los sistemas operativos de Windows, macOS y Linux. Probablemente utilices Windows, por lo que, debes descargar e instalar el archivo base.

![](images/Screenshot3.png)

## Instalación de R

La instalación es simple, puedes realizarla sin mayor complicación pero si tienes alguna duda solo sigue el siguiente vídeo.

{{< video src="/aprender/instalacion.mp4" type="video/mp4" preload="auto" >}}

## Ejecución de R

Una vez instalado R, podemos ejecutarlo y utilizarlo directamente desde la consola que nos mostrará lo siguiente

![](images/Screenshot4.png)

La versión instalada junto a algo de información y consejos del programa, además en la línea en rojo \> podemos interactuar con este lenguaje.

### Hola Mundo

Anteriormente en la cápsula [2. La necesidad de la programación letrada](https://abeluis.netlify.app/aprender/programacion-letrada/) dejé un bloque de código de ejemplo, ejecútalo en la consola de R para ver que sucede.

Esto es solo el principio, en la siguiente cápsula instalaremos Rstudio y realizaremos algunos ejemplos para conocer una herramienta fundamental en la programación en R.
