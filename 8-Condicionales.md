# Condicionales
Los condicionales son una parte muy importante del mundo de la programación. Poder hacer diferentes cosas evaluando la situación de tu código es muy importante.


## Tipos de Condicionales

### IF
Este condicional se utiliza para ejecutar una acción en el caso de que sea true el resultado dentro de este condicional.
Ejemplo:
```js
if(100 < 10000){
    console.log("100 es más pequeño que 10000");
}
```
En este caso si que se ejecutaría el console.log() ya que 100 es más pequeño que 10000 y por lo tanto esa expresión de operador daría true.


### IF, ELSE
Este condicional es una extensión del if en la cual añadimos código que se ejecutaría si el resultado dentro del condicional fuese false.
Ejemplo:
```js
if(100 > 10000){
    console.log("100 es más grande que 10000");
} else {
    console.log("100 es más pequeño que 10000");
}
```
En este caso, dado que 100 NO es más grande que 10000, se ejecutaría el segundo console.log.

### ELSE IF
Este condicional es una combinación de los dos primeros condicionales. Este sirve para dar múltiples opciones a if.
Ejemplo:
```js
let numero = 1;

if(numero === 0){
    console.log("Tu numero es 0.")
} else if(numero === 1){
    console.log("Tu numero es 1.");
} else {
    console.log("Tu numero no es ni 1 ni 0.")
}
```
En este caso, si la variable "numero" fuera 0, se ejecutaría el primer console.log. Pero en el caso de que no lo fuera, el código miraría si es 1 también gracias al else if. Pero si no es ninguno de los dos se entraría al console.log final.


### SWITCH
Este es una combinación de todos los anteriores. Normalmente se usa para no tener que escribir siempre else if, else if else if aunque es lo que hace este condicional al final.
Ejemplo:
```js
let numero = 12231;

switch(numero){
    case 0:
        console.log("Tu numero es 0");
        break;
    case 1:
        console.log("Tu numero es 1");
        break;
    case 2:
        console.log("Tu numero es 2");
        break;
    default:
        console.log("Tu numero no está en este código switch.");
        break;
}
```
Como podemos observar, la sintaxis de este condicional es muy diferente a los demás y no entraremos en mucho detalle. Pero se podría considerar que "case" es un if o else if y el "default" es else.

Te invito a que experimentes con estos condicionales en tu propio editor, incluso con el switch si quieres aprender como funciona.

[< Anterior](./7-Comparadores.md) [Siguiente >](./9-Puertas-Lógicas.md)