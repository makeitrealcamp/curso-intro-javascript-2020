# Ejercicios día 8

Recuerda que puedes hacer preguntas en el [Foro de Make It Real](https://foro.makeitreal.camp/c/curso-javascript-sept-2020/6).

## Ejercicio 41

Crea una **función constructora** llamada `Producto` que reciba dos argumentos: el nombre y el precio. La función deberá inicializar las propiedades nombre y precio del objeto con los valores que llegan como parámetros.

A continuación mostramos algunos ejemplos de la forma en la que se va a utilizar esta **función constructora**:

```javascript
// escribe tu función constructora acá

// código de prueba
const pan = new Producto("Pan", 2.5)
console.log(pan.nombre) // "Pan"
console.log(pan.precio) // 2.5

const leche = new Producto("Leche", 3.7)
console.log(leche.nombre) // "Leche"
console.log(leche.peso) // 3.7
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-41/537). No incluyas el código de prueba.

## Ejercicio 42

Crea una **función constructora** llamada `Person` que reciba tres argumentos: el nombre, el peso y la estatura. La función deberá inicializar las propiedades `name`, `weight`, `height` con los valores que llegan como parámetros.

Agrega dos métodos a la función constructora Persona: `greet` y `bmi`.

`greet` debe recibir un nombre y retornar el string `"Hola X, me llamo Y"` donde `X` es el argumento que se recibe y `Y` es la propiedad `name` del objeto.

`bmi` no recibe ningún argumento y retorna el índice de masa corporal que se calcula con la siguiente fórmula:

`peso / altura^2`

A continuación mostramos algunos ejemplos de la forma en la que se va a utilizar esta **función constructora** y sus métodos:

```javascript
// escribe acá tu solución

// código de prueba
const pedro = new Person("Pedro", 72, 1.5)
console.log(pedro.greet("Maria")) // "Hola Maria, me llamo Pedro"
console.log(pedro.bmi()) // 32
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-42/538). No incluyas el código de prueba.

## Ejercicio 43

Crea una **función constructora** llamada `Auto` que no reciba ningún argumento pero inicializa una propiedad llamada velocidad en 0.

Agrega dos métodos al prototipo de la función constructora:

* `acelerar`: recibe un número como argumento e **incrementa** la propiedad velocidad de acuerdo al número.
* `frenar`: recibe un número como argumento y **decrementa** la propiedad velocidad de acuerdo al número. Sin embargo, si la velocidad terminara siendo negativa debe quedar en 0.

Un ejemplo de cómo utilizaríamos esta función constructora:

```javascript
// escribe tu solución acá

// código de prueba
const a1 = new Auto()
console.log(a1.velocidad) // 0

a1.acelerar(1)
a1.acelerar(2)
console.log(a1.velocidad) // 3

a1.frenar(2)
console.log(a1.velocidad) // 2
a1.frenar(3)
// la velocidad quedaría en -1, así que se deja en 0
console.log(a1.velocidad) // 0
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-43/539). No incluyas el código de prueba.

## Ejercicio 44

Agrega un método llamado `promedio` a la función constructora `Array` que retorne el promedio de los elementos en el arreglo:

```javascript
// escribe tu solución acá

// código de prueba
console.log([1, 2, 3, 4].promedio()) // 2.5
console.log([7, 8, 9].promedio()) // 8
console.log([300, 100].promedio()) // 200
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-44/540). No incluyas el código de prueba.

## Ejercicio 45

Agrega un nuevo método llamado `palindrome` al prototipo de `String` que retorne `true` si el string es un palíndrome, `false` de lo contrario.

Recuerda que un palíndrome es una frase que se lee igual de izquierda a derecha que de derecha a izquierda (excluyendo los espacios en blanco):

```javascript
// escribe tu solución acá

// código de prueba
console.log("anita lava la tina".palindrome()) // true
console.log("aman a panama".palindrome()) // true
console.log("hola mundo".palindrome()) // false
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-45/541). No incluyas el código de prueba.
