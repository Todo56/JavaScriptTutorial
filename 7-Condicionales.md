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


### SWITCH

[< Anterior](./6-Operadores.md) [Siguiente >](./8-Puertas-Lógicas.md)