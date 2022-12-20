# MARKDOWN

Markdown es un lenguaje de marcado ligero, una forma de agregar formatos como encabezados, negritas, cursivas, listas... a un texto sin formato utilizando un editor de texto simple. Es decir, una forma rápida de coger apuntes con ordenador y pasarlos a limpio en un solo paso.  

    -  Elementos de bloque
       -  Párrafos
       -  Saltos de línea
       -  Encabezados
       -  Citas
       -  Listas
       -  Código de bloque
       -  Línea horizontales
    -  Elementos de linea
       -  Énfasis
       -  Links o enlaces
       -  Código
       -  Imágenes
    -  Otros elementos
       -  Links automáticos
       -  Omitir Markdown
       -  Símbolos matemáticos

# Saltos de bloque (=Párrafos)
Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces INTRO) `Ejemplo:`

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Saltos de línea (=lineas de texto)
Para realizar  un salto de linea y empezar una frase en una linea siguiente dentro del mismo parrafo, tendras que pulsar **dos veces** la barra espaciadora antes de pulsar una vez INTRO.`Ejemplo:`

Nombre:  
Apellidos:  
Dirección:


# Encabezados  
Las almohadillas o hastag `#` es el método utilizado en Markdown para crear encabezados. Debes usarlos añadiendo uno por cada nivel y dejando un espacio en blanco. `Ejemplo:`  
## Encabezado 2
### Encabezado 3
#### Encabezado 4
#### Encabezado 5
###### Encabezado 6


# Enfantizar: negritas y/o cursivas   
Para poner cursivas encierra entre 1 asterisco. Para poner negritas encierra entre 2 asteriscos. Para poner negritas y cursiva encierra entre 3 asteriscos.`Ejemplos:`  
Lorem ipsum *dolor* sit **amet**, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut ***labore et dolore*** magna aliqua.  
# Líneas horizontales
Para crearlas, en una línea en blanco deberás incluir `tres` de los siguientes elementos: 3 asteriscos, 3 guiones, o 3 guiones bajos. `Ejemplo`  
***
---
___
# Citas
Las citas se generan utilizando el carácter mayor que `>` al comienzo del bloque de texto. `Ejemplo:`  
> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
# Listas
Para crear listas desordenadas podemos utilizar 3 tipos de simbolos por cada item de la lista: Un asterisco `*`, un guión medio `-` o un símbolo más `+`. `Ejemplo:`  


+ Item 1
+ Item 2
+ Item 3 
  
Para crear listas ordenadas debes utilizar la sintaxis de tipo: `1.`
1. Ítem 1
2. Ítem 1
3. Ítem 1
# Links o enlaces
Se crean escribiendo la palabra o texto enlazada entre `[]` corchetes, y el link en cuestión entre `()` paréntesis.

Sin texto enlazado escribe la URL entre ángulos `< URL >` Enlace de ejemplo como referencia:  <https://lamborghini.com> y al final del texto escribir la etiqueta seguida de dos puntos.
# Imágenes
Insertar una imagen con Markdown se realiza de una manera idéntica a insertar links. En este caso, debes añadir un símbolo de `!` exclamación al principio y el enlace que es la ubicación de la imagen.  

      ![Balon de Futbol](/balon.jpg "Balon de futbol")

`Ejemplo:`
![Balon de Futbol](/balon.jpg "Balon de futbol" )
# Tablas
Markdown permite dibujar tablas mediante plecas `|`. Cada celda está separada por uno de estos caracteres. Para crear encabezados que se distingan visualmente del resto del contenido, se subrayan las celdas correspondientes con guiones `-`. `Ejemplo:`


| **Columna 1** |**Columna 2**|
|--|--|
|uno|dos|
|tres|cuatro|
|cinco|seis|
# Línea de Código
Encerrando el código entre acentos graves `<html lang="es">`
# Bloque de Código
Para crear un bloque entero que contenga código lo único que tienes que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ~ virguillas o tres acentos graves. La otra manera de añadir código en Markdown es comenzar el párrafo con `cuatro espacios en blanco`. `Ejemplo:`
~~~ 
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Document</title>
</head>
~~~
# Omitir Markdown
Cómo escribir ciertos símbolos como * o #, sin que Markdown los interprete para convertirlos en negritas,...
Escribiendo justo delante del símbolo la barra invertida ´\´.´Ejemplo:´ Esto es un asterisco *
# Escritura Matemática

+ Fórmulas en línea: 
$(a+b)² = a² + b² + 2ab$

+ Radicales:
$$\sqrt{a² - b²}$$

+ Fracciones;
$$
x=\frac{-b\pm\sqrt{b^2-4 a c}}{2a}.
$$

+ Paréntesis grandes:
$$\left(\sqrt{x²}\right)²$$

+ Colores:
$$\textcolor{yellow}{A}aBb123$$