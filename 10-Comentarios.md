# Comentarios
Ahora, introduciremos un concepto que se ha estado utilizando durante todo este tutorial para descansar de todos estos conceptos nuevos y extraños: los comentarios. Los comentarios son líneas de texto en el código que se ignorarán a la hora de ejecutarlo. Estos se usan para marcar ciertos aspectos de tu código, separarlo, para que no se ejecute código sin necesidad de borrarlo...

## Comentarios de una sola línea
Estos comentarios sirven para separar, dar contexto a ciertas líneas de código o borrar líneas solas de código. Todo lo que esté detrás de las "//" se ignorará.

```js
// Esto mostrará "True!" | COMENTARIO
while(true){
    console.log("True!"); // También podemos poner el comentario aquí!
}
```

## Comentarios de diversas líneas
Estos comentarios se pueden utilizar para remover gran cantidades de código problemático o para poner comentarios entre partes de código. Estos comentarios comienzan donde pones `"/*"` y acaban donde pones `"*/". 

```js
let decirAlgo = true;

console.log("Comenzando el programa.");
/*
Comentanos ese código porque daría error (falta un paréntesis).
if(decirAlgo){
    console.log("Debo decir algo";
}
*/

```
[< Anterior](./9-Loops.md) [Siguiente >](./11-Funciones.md)