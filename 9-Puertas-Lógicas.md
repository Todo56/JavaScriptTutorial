# Puertas Lógicas
Las puertas lógicas son muy importantes en el mundo de la programación y electrónica, nos permiten hacer mucho en poco código. Obviamente hay más puertas lógicas pero estas son las más importantes, y por ejemplo, la puerta NAND se podría hacer combinando la NOT y AND.

## NOT
Puerta lógica cambia el valor del resultado. Significa que si le damos "true", saldrá "false".
Ejemplo:
```js
let variable = false;

if(!variable){
    console.log("Variable no está puesta.");
}
```
En este caso el console.log se ejecutaría.

## OR
Esta puerta lógicas sirve para comparar varios valores y en el caso de que alguno sea "true" se ejecutará el código dentro del condicional.
```js
let ventanaAbierta = true;
let puertaAbierta = false;

if(ventanaAbierta || puertaAbierta){
    console.log("Alarma suena.");
}

```

## AND
Esta puerta lógica sirve para ejecutar una pieza de código solo si dos variables son "true".
```js
let trenEnLaEstacion = true;
let trenParado = true;

if(trenEnLaEstacion && trenParado){
    console.log("Se deben abrir las puertas.");
}
```

[< Anterior](./8-Condicionales.md) [Siguiente >](./10-Loops.md)