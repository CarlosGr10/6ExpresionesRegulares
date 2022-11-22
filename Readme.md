# Curso de Expresiones Regulares

Las expresiones regulares son patrones de caracteres que te permite ir seleccionando o descartando datos en un archivo de texto como por ejemplo csv, o en una línea o un input, según coincidan o nó con este patrón.

Debes ser muy selectivo y especifico en ellas para encontrar lo que verdadermente necesitas.

Son filtros extremadamente poderosos y puntuales.

## Explicado con palitos y bolitas

Pueden haber patrones donde podemos filtrar de forma ma80 medleys sencilla

![](https://i.imgur.com/SEUO9Db.png)

### Aplicaciones de las expresiones regulares

Busquedas mas optimizadas

Herramientas que nos va ayudar este curso 

**Indexadores**

[Rebular](https://rubular.com/r/xcutzuAxvcGx8t)

[Regex 101](https://regex101.com/)

**Ducumentos** 

[Expresiones Regulares PDF](https://www.carlosramirezflores.com/regular-expressions.pdf)


[Ejemplos de expresiones regurares](https://medium.com/@jmz12/expresiones-regulares-215af64acab1)


# El raracter (.)

Encuentra todos los caracteres de un archivo, y lo que hace es seleccionar caracter a caracter 

![](https://i.imgur.com/Q2nqzdm.png)

En este ejemplo la expresion regular remplazo cada caracter por otro

![](https://i.imgur.com/j1ntaAe.png)

Este es una expresion poderosa, en este ejemplo encontramos que podemos buscar 
un caracter que tenga un espacio

![](https://i.imgur.com/8iF9tzQ.png)

Ahora, si nos damos cuenta, la logica es que busca caracteres de forma logica
si agregamos 10 puntos, buscara cadenas que contengan 10 puntos, incluyendo espacios
**La unico es que no tiene restricciones, toma numeros y letras por igual**

![](https://i.imgur.com/X7JSaU3.png)

El punto toma grupos de caracteres 

# Las clases predefinidas y construidas

## Digitos

Una de las expresines regulares básicas es la busqueda de digitos
para ello nosotros utilizamos "\d"

![](https://i.imgur.com/7z42jXl.png)

Y tambien al igual que el punto tambien busca por grupos 

![](https://i.imgur.com/cBwuepr.png)

## Word (Palabras)

All word characters, Encuentra todos los caracteres que son parte de una palabra, tanto letras (minúsculas o mayúsculas) como números, es equivalente a poner [a-zA-Z0-9_].

![](https://i.imgur.com/rclnosw.png)

Aplica tambien la busqueda para grupos

![](https://i.imgur.com/4DdCudb.png)

## Spaces

Espacios (los saltos de línea y tabuladores también son espacios).

![](https://i.imgur.com/mMfD6HX.png)

## Busqueda de rangos

Para hacer una busqueda mas potente con digitos los encerramos entre conchetes y ponemos nuestro rango

![](https://i.imgur.com/MG0tPvM.png)

Tambien lo podemos aplicar con las palabras

![](https://i.imgur.com/2sRZ0aT.png)

Nota: Para poder obtener el caracter punto , y no la clase operadora punto
escapamos el caracter "\."

![](https://i.imgur.com/rEOOP1w.png)

**Contruyendo una expresion regular con lo aprendido**

![](https://i.imgur.com/IsAYO59.png)

Con esto expresamos que queremos buscar de al a hasta la c en minusculas, de la A hasta la F en mayusculas, del 0 al 4, que tome en cuenta los guiones y los puntos 























