# Ejercicios día 10

Recuerda que puedes hacer preguntas en el [Foro de Make It Real](https://foro.makeitreal.camp/c/curso-javascript-sept-2020/6).

## Ejercicio 51

Escribe una función llamada `reducirACero` que reciba un número no negativo y retorne el número de pasos que son necesarios para convertirlo a cero (0) siguiendo estas reglas:

* Si el número actual es par, dividirlo por dos.
* Si el número actual es impar, restarle 1.

Por ejemplo, si el número de entrada es 7 necesitaríamos 5 pasos:

1. 7 es impar, así que le restamos 1 y obtenemos 6.
2. 6 es par, así que lo dividimos por 2 y obtenemos 3.
3. 3 es impar, así que le restamos 1 y obtenemos 2.
4. 2 es par, así que lo dividimos por 2 y obtenemos 1.
5. 1 es impar, así que restamos 1 y obtenemos 0!

```javascript
// escribe tu función acá

// código de prueba
console.log(reducirACero(7)) // 5
console.log(reducirACero(123)) // 12
console.log(reducirACero(8)) // 4
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-51/562). No incluyas el código de prueba.

## Ejercicio 52

Escribe una función llamada `transcribir` que reciba un string (una cadena de ADN) y retorne otro string (su complemento ARN).

Los complementos son los siguientes:

* G -> C
* C -> G
* T -> A
* A -> U

```javascript
// escribe tu función acá

// código de prueba
console.log(transcribir("ACGT")) // UGCA
console.log(transcribir("ACGTGGTCTTAA")) // UGCACCAGAAUU
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-52/563). No incluyas el código de prueba.

## Ejercicio 53

Escribir una función llamada triqui que reciba un argumento board (un arreglo de arreglos) y retorne true si hay triqui, false de lo contrario.

```javascript
// escribe tu función acá

// código de prueba
const b1 = [
  ["X", "O", "-"],
  ["O", "O", "X"],
  ["-", "O", "X"]
]
console.log(triqui(b1)) // true

const b2 = [
  ["X", "X", "-"],
  ["O", "O", "X"],
  ["-", "O", "X"]
]
console.log(triqui(b2)) // false
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-53/564). No incluyas el código de prueba.

## Ejercicio 54

Escribe una función llamada `removerCeros` que reciba un arreglo de números y retorne un nuevo arreglo sin los ceros:

```javascript
// escribe tu función acá

// código de prueba
removerCeros([1, 0, 2, 0, 3, 0]) // [1, 2, 3]
removerCeros([1, 2, 3]) // [1, 2, 3]
removerCeros([0, 0, 0]) // []
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-54/565). No incluyas el código de prueba.

## Ejercicio 55

Escribir una función llamada `ordenar` que reciba un arreglo y retorne un nuevo arreglo ordenado. Sigue estos pasos para implementar esta función:

1. Crea un arreglo vacío.
2. Recorre el arreglo original (el argumento) y encuentra el menor.
3. Inserta el elemento en el otro arreglo y elimínalo del arreglo original.
4. Vuelve al paso 2 hasta que el arreglo original esté vacío.

```javascript
// escribe tu función acá

// código de prueba
console.log(ordenar([6, 2, 9, 7, 8, 3])) // [2, 3, 6, 7, 8, 9]
console.log(ordenar[5, 4, 3, 2, 1]) // [1, 2, 3, 4, 5]
console.log(ordenar[1, 2, 3]) // [1, 2, 3]
```

**Nota:** No utilices el método `sort` de JavaScript.

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-55/566). No incluyas el código de prueba.

## Ejercicio 56

Escribe una función llamada `sumarImpares` que reciba un arreglo y sume todos los números impares que se encuentren en el arreglo:

```javascript
// escribe tu función acá

// código de prueba
console.log(sumarImpares([1, 2, 3, 4, 5])) // 9
console.log(sumarImpares([2, 4])) // 0
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-56/567). No incluyas el código de prueba.

## Ejercicio 57

Escribe una función llamada `numDuplicados` que reciba un string y retorne el número de caracteres que aparecen más de una vez.

```javascript
// escribe tu función acá

// código de prueba
console.log(numDuplicados("abcaa")) // 1
console.log(numDuplicados("abab")) // 2
console.log(numDuplicados("abc")) // 0
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-57/568). No incluyas el código de prueba.

## Ejercicio 58

Escribe una función llamada `escalera` que reciba un número como argumento. La función debe retornar una cadena de texto (string) en forma de escalera como en el siguiente ejemplo:

```javascript
// escribe tu función acá

// código de prueba
console.log(escalera(2))
// #
// ##

console.log(escalera(3))
// #
// ##
// ###

console.log(escalera(5))
// #
// ##
// ###
// ####
// #####
```

La primera línea del string tiene un signo de número (#), la segunda dos, y así sucesivamente hasta el número que ingresó el usuario.

**Nota**: Recuerda que para representar un salto de línea en un string debes utilizar el caracter `\n`.

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-58/569). No incluyas el código de prueba.

## Ejercicio 59

Escribe una función llamada `max` que reciba un objeto y retorne la llave que tenga el mayor valor:

**Nota:** Puedes asumir que sólo hay un valor máximo

```javascript
console.log(max({ a: 1, b: 6, c: 3 })) // b
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-59/570). No incluyas el código de prueba.
