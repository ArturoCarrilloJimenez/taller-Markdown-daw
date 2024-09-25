<!-- Prueba de todos las posibles etiquetas con Markdown -->
# Repositorio de ejemplos de Markdown

Este repositorio tiene ejempolo de las etiquetas de marcado en Markdown

<br/>

## Ejemplos de cabeceras

## Con 2 # Pondremos un h2
### Con 3 # Pondremos un h3

###### Esto sigue asi hasta el h6

Este se forma con ` # `, cada uno de estos representa un volor, es decir, si tenemos 3, estaremos poniendo un h3 

##  Ejemplos de texto en negrita y cursiva

__Esto es un texto en negrita, se consige con 2 barras bajas__

_Esto es un texto en cursiva, se consige con una sola barra baja_

## Ejemplos de codigo

Este da formato a un comando como `ls -la`, este formato se consige con las tildes ` '' `

```  py
print("Hello")
```

El bloque de codigo sin encambio se consige con 3 tildes seguidas ` ``` codigo ``` ` 

## Ejemplos de link

Enlace a una web o archivo `[text](url/ruta)`

* [Pagina de esta actividad](https://josejuansanchez.org/iaw/taller-markdown/index.html)


* [Link al segundo archivo de Markdown](file.md)

## Ejemplo de imagen

Esto se realiza de forma parecida a un link, este tiene la sigiente estuructura: `![texto en caso de que no carge](url/ruta)`

![gato](img/gratisography-cyber-kitty-800x525.jpg)

## Ejemlo de listado

### Lista de puntos

Se forma de la siguiente manera:

``` md
* Punto 1
* Punto 2
    * Punto 2.1
* Punto 3
```

* Punto 1
* Punto 2
    * Punto 2.1
* Punto 3

### Lista ordenada por numeracion

Se forma de la siguiente manera:

``` md
1. Item 1  
  1.1 Item 1.1  
  1.2 Item 1.2 
```

1. Item 1  
  1.1 Item 1.1  
  1.2 Item 1.2 

## Ejemplo de tablas

Para realizar una tabla tendremos la siguiente estructura

``` md
| Cabecera 1 | Cabecera 2 
| --- |--- 
| Fila 1 | Fila 2
| Fila 3 | Fila 4
```

| Cabecera 1 | Cabecera 2 
| --- |--- 
| Fila 1 | Fila 2
| Fila 3 | Fila 4

## Ejemplo de citas

> Esto es una cita de texto, este se forma con el  caracter ` > ` al inicio de esta