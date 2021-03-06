# Variables
A veces, como programador te conviene guardar valores en el código para que puedas utilizarlos más tarde o varias veces sin tener que repetirlos. También te puede interesar para operar el valor. Para eso se utilizan las variables, estas se guardan en la memoria RAM i se pueden utilizar dentro del bloque de código.

## Tipos de Variables
Las variables se pueden declarar utilizando los siguientes tipos de variables. Normalmente al declarar las variables se utiliza una ";" para decir al ordenador que se ha acabado la línea de código.

### Let
Let es una variable que se puede modificar, pero no utilizando otro let.
```js
let variable1 = "A";

variable1 = "Hola";

console.log(variable1); // MOSTRARÁ "Hola"

// ESTO ES "ILEGAL" (Soltará un error ya que no podemos declarar con let la misma variable):
let variable1 = "dqdqw"; 
```

### Const
Const es una constante, esta variable NO se puede modificar.
```js
const constVariable = "Hola";

// ESTO ES "ILEGAL" (Soltará un error):
const constVariable = "A";
```

### Var (deprecado)
Var es un tipo de variable que se puede cambiar cuando quieras. Pero esta variable ya está deprecada por lo tanto no se utiliza hoy en día. 
Ejemplo:
```js
var varVariable = "Hello World";

var varVariable = "Hola Mundo";
```

## Tipos de Valores de Variables
Estos tipos de valores se pueden aplicar a varios lenguajes pero a veces cambian, por lo tanto se deben considerar valores para JavaScript.

### String
El valor string es una frase o palabra. Se representa entre comillas. Se pueden utilizar todas estas comillas: ", ', `.
Estos son ejemplos de strings:
```js
let string = "";
let string = '';
let string = ``;
```

### Boolean
Los valores Boolean son valores que solo pueden ser positivos o negativos. Es decir, solo puede ser 0 (false) o 1 (true). Estos son esenciales para trabajar los operadores, condicionales y las puertas lógicas.
```js
let bool1 = true;
let bool2 = false;
```

### Integer
El valor integer es un número. Este puede ser negativo y positivo, pero no decimal.
Estos son ejemplos de strings:
```js
let integer = 1;
let integer = 100002301243;
let integer = -12423;
```

### Float
Este valor es un número con valores decimales. En programación no se utilizan las "," si no que se utiliza el "." como en America. También se puede utilizar valores negativos.
```js
let float = 1.345132;
let float = 131243424132.2131234;
let float = -12124.124
```

### Object
Esta es una manera de guardar como sub apartados en variables que se puede utilizar. Por lo tanto se puede definir variables dentro de esa misma variable.
```js
let object = {
    variable1: "jajajja",
    variable2: 2131324,
    variable3: 12434.2314,
    variable4: {
        variable5: "Puedo poner otro 'object' dento de un subapartado."
    }
}
```

Para acceder estos valores nos debemos centrar en la "key". En este caso podemos observar las "keys": variable1, variable2, variable3 y variable4. Estas "keys" nos dejarán acceder a los "values", valores.
Para obtener los valores se pueden obtener de estas maneras:
```js
console.log(object["variable1"]); // Obtendríamos "jajajja"
console.log(object.variable1); // Obtendríamos "jajajja"
```

### Array
Los array son listas de variables.
```js
let array = [
    "variable1",
    "variable2",
    ["variable1"]
];

```

Te invito a que experimentes con los tipos de variables.

[< Anterior](./4-Hello-World.md) [Siguiente >](./6-Operadores.md)