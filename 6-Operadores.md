# Operadores
En programación, los operadores nos permiten comparar dos números. Al comparar dos números, siempre nos dará un valor que será un bool. Es decir, true  o false.

## Lista de Operadores de JavaScript
- ==  | Igual débil.
- === | Igual estricto.
- <   | Más pequeño que.
- >   | Más grande que.
- <=  | Más pequeño o igual que.
- >=  | Más grande o igual que.

Se puede observar que estos operadores son bastante similares a los que se pueden encontrar en matemáticas. Pero siempre hay que remarcar la diferencia ente el igual débil y el igual estricto.

En este caso, el igual débil respondería que es cierto ya que no tiene en cuenta el tipo de la variable.
```js
console.log("1" == 1); // Pondría true.
```

El igual estricto, requiere que las variables sean IDENTICAS, por lo tanto este sería el resultado:
```js
console.log("1" === 1); // Pondría false.
```

[< Anterior](./5-Variables.md) [Siguiente >](./7-Condicionales.md)