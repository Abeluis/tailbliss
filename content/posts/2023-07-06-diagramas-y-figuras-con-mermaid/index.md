---
title: "Diagramas y figuras con Mermaid"
date: 2023-07-06
draft: false
language: es
featured_image: ../assets/images/pana/mapa.png
summary: Hechas con Markdown y Javascript.
description: Hechas con Markdown y Javascript.
author: Abel_Luis
authorimage: ..//assets/images/global/author.webp
categories: blog
tags: 
 - Markdown
 - Javascript
 - Blogdown
mermaid: true
---

Estuve trabajando en una página que me servirá como Demo para mostrar a organizaciones que quieran una página web y que también formará parte de mi portafolio. La página es [Tramitados](https://tramitados.netlify.app/) y utiliza el tema [Tella](https://github.com/opera7133/tella) que he personalizado un poco. Aún me faltan cosas visuales como que el slider muestre botones negros y que el texto que está en el mismo esté en negrita o que se aplique un cuadro en el centro para tener mayor contraste entre el texto y la imagen del slider. Pero volviendo al tema de esta publicación, en esa página en la sección de transparencia hice unos gráficos de torta que resultaron fáciles de replicar gracias a [Mermaid](https://mermaid.js.org/) que permite crear diagramas a través de javascript con formato Markdown.

La instalación es algo más complicada que otras funcionalidades que han sido solo shortcodes de Hugo, pero la encuentro útil para hacer diagramas minimalistas y que no afecten los tiempos de carga o requieran generar algo en otro programa ya que hay documentación y también el [editor online](https://mermaid.live/) de Mermaid tiene plantillas de diagramas de flujo, secuencias, clases, estados, Gantt, lineas de tiempo, mapas mentales, quadrantchart, entre otros.

Diagrama de flujo de Lámpara que no funciona

{{< mermaid >}}
flowchart TD
    A[La lámpara no funciona] --> B{Está enchufada la lámpara?}
    B -- Si --> C{Está quemada la ampolleta?}
    C -- Si --> D[Cambiar la ampolleta]
    C -- No --> F[Comprar una nueva lámpara]
    B -- No ----> E[Enchufar la lámpara]
    
{{< /mermaid >}}

Diagrama de linea de tiempo presidentes de Chile desde el 2000

{{< mermaid >}}
timeline
title Presidentes de Chile desde el 2000
section Anteriores
    2000 : Ricardo Lagos Escobar
    2006 : Michelle Bachelet Jeria
    2010 : Sebastián Piñera Echeñique
    2014 : Michelle Bachelet Jeria
    2018 : Sebastián Piñera Echeñique
section Actual
    2022 : Gabriel Boric Font
    
{{< /mermaid >}}

Gráfico de torta Frutas en la frutera

{{< mermaid >}}
pie title Frutas en la frutera
    "Plátanos" : 4
    "Manzanas" : 3
    "Peras" : 2
    "Naranjas": 5
    "Chirimoyas": 2
    "Kiwis": 4
{{< /mermaid >}}

El tutorial para "instalar" Mermaid en blogdown y que funcione con Hugo es de Navendu Pottekkat disponible en el siguiente enlace \> [Adding Diagrams to Your Hugo Blog With Mermaid](https://navendu.me/posts/adding-diagrams-to-your-hugo-blog-with-mermaid/).
