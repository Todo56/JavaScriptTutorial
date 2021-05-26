# Loops (Bucles)
Los bucles son también unas herramientas muy importantes para los programadores. Utilizando bucles puedes automatizar ciertos aspectos de tu código.

## While
Este bucle sirve para hacer algo mientras una expressión dentro de él sea "true". También se podría hacer un loop infinito utilizando el siguiente código.

```js


while(true){
    console.log("Hola")
    /*
    Este es un código peligroso, si se ejecuta no parará nunca a no ser que pares el proceso utilizando control+c en la terminal o apagues el ordenador. Si lo ejecutas, tu ordenador comenzará a gastar muchos recursos y saldrán muchos "Hola".
    */
}


let variable = 0;
while(variable < 10){
    console.log(variable)
    variable = variable + 1;
}
/*
Este código contaría hasta 9 como se puede ver más abajo. ¿Sabes porque?
*/


```

![8](./assets/images/8.png)

## Do X While

## Foreach

## For

[< Anterior](./8-Puertas-Lógicas.md) [Siguiente >](./10-Comentarios.md)