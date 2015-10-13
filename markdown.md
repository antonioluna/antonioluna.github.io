---
layout: markdown
Tag: Aprendiendo MarkDown
title: Aprendiendo MarkDown
---

{% comment %} 
    Se pueden estipular variables entre las lineas "---". Cada variable se invocará con "page.variable".
    En esta sección tambien pueden asignarse plantillas en formato html junto al lenguage "liquid", dichas plantillas deben encontrarse en un directorio llamado _layouts en la raiz del sitio. 
{% endcomment %}


{% comment %} 
    En esta sección se crea un párrafo común (etiquetas <p> </p>). Para hacer un salto de línea se dejan dos espacios en blanco. Para crear otro párrafo se usa dos retornos de carro (tecla enter)
{% endcomment %}

{% comment %} 
    Los encabezados h1 - 6 se realiza colocando "#" al principio de la línea. Por ejemplo: #Esto es h1, ##esto es h2
{% endcomment %}

#Aprendiendo MarkDown

Este artículo está escrito en el lenguaje de marcas "Markdown". Para su mejor comprensión, en esta página no se ha usado hoja de estilo de ningún tipo.  

Markdown fue desarrollado por los ingenieros  **John Gruber** y **Aaron Swartz** para facilitar la publicación de páginas web.

En [este enlace](https://raw.githubusercontent.com/antonioluna/antonioluna.github.io/master/markdown.md) podrás ver la sintaxis del documento markdown utilizado para crear esta entrada.

##Uso de listas:  
Para crear una lista solo debemos poner un asterisco "*" al principio de la línea.  

* Esto pertenece a una lista desordenada
* Esto es otro elemento de desordenada

##Uso de listas ordenadas:  
Para crear una lista ordenada sólo debemos poner la numeración al principio de la linea del texto:

1. Primer elemento de una lista ordenada
2. Segundo elemento de una lista ordenada

##Uso de tablas:
Para usar una tabla debemos poner líneas de puntos "| --- | --- |":  

| Columna 1 | Columna 2 |
| :-------: | :-------: |
| fila 1, 1 | fila 1, 2 |
| fila 2, 1 | fila 2, 2 |

##Introducción de código:  
Para introducir código sólo hay que tabular al principio de la línea:  

	import os

[volver al índice](https://antonioluna.github.io)