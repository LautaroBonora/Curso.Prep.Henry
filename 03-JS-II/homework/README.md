# Homework: Javascript II

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `for`
* `&&`, `||`, `!`

2. Desde la carpeta `Prep` en la carpeta donde clonaste el repo, ingresa el comando `npm test JSII.test.js` para correr los tests automatizados. Al principio, todos los tests estarán fallados/rotos. Encontrarás las funciones para hacer pasar los tests en el archivo `homework.js`.

### Aca tendras acceso a las [Soluciones](https://github.com/atralice/Curso.Prep.Henry/blob/solution/03-JS-II/homework/homework.js)

1.  Para poder comparar dos expresiones de igualdad necesitamos de operadores: Así como están los matemáticos (+,-, %), en este caso usaremos los llamados operadores lógicos.

    El primero de ellos se llama "Y" o "AND" en inglés, y se escribe `&&`; sólo nos devolvera verdadero o "True" cuando AMBAS expresiones sean VERDADERAS; ej: 1 >= 1 && 1 < 2 // TRUE ; 1 > 1 && 3 > 2 // FALSE porque la primer expresión es falsa.-

    El segundo operador lo denominamos como "Ó" u "OR" en inglés; lo representamos con dos barras verticales
     `||`, y a diferencia del "&&", sólo necesitamos que una de las expresiones sea verdadera o "True" para que nos devuelva un "True" y de esta forma se ejecute el código, como por ejemplo: 3 > 1 || 2 < 2 // TRUE

    El tercero y último operador se nombra "NOT" en inglés o "NO"; se lo escribe sencillamente con un `!`, y lo que hace es volver opuesto el resultado que se obtiene en un expresión.                                 Como ejemplo decimos que if (!(2 > 1)) // FALSE ya que la expresión es Verdadera, y como el "!" nos devuelve el valor contrario, el código no se ejecutará.-

    Para entender lo que es un BUCLE lo comparamos con una rueda de ratón: El sistema "rueda ratón" representa el `for`, que va repetirse, es decir, a ejecutarse las veces que sean necesarias hasta que lleguemos a lo que necesitamos (a una recompensa como un pedazo de queso), o que nuestro "ratón" se detenga por algo que "encontró" en su camino.
    Esta "rueda" o bucle 'for' tiene tres partes entre () que deben estar si o si:
        Primero establecemos a partir de que vuelta parte nuestro "ratón", si desde la vuelta 0, 50, o 100;
        después le indicamos cuantas "vueltas" debe dar la rueda hasta pararse, es decir, indicamos una condición de salida;
        por último, señalamos a que "velocidad" correra el "ratón", es decir, las vueltas que da por segundo. Ejemplo:

        for (desde que vuelta parte el ratón; a que nro. de vueltas debe llegar; velocidad del ratón)