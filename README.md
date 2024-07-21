
# CONOCIENDO KOTLIN

Kotlin es un lenguaje de programación moderno y multiplataforma desarrollado por JetBrains.


## Definición de Variables

En Kotlin, las variables se definen usando las palabras clave val y var:

 - val: Para variables inmutables (constantes).
 - var: Para variables mutables.

 ### Ejemplo:

val pi = 3.14 // Variable constante

var contador = 0 // Variable mutable

## Manejo de nulos

Kotlin aborda el problema de los valores nulos de manera segura con el sistema de tipos:
- Para permitir valores nulos, se usa el tipo seguido de ?.

- Para evitar valores nulos, se usa el operador !! o se usa el operador de verificación ?..

### Ejemplo:

var cadena: String? = null // Variable que puede ser nula

var longitud = cadena?.length // Operador de verificación nula

## Opciones
Kotlin ofrece varias características poderosas:

- Interoperabilidad: Puede interactuar con código Java existente.
- Funciones de extensión: Extienden las clases existentes con nuevas funcionalidades.
- Corrutinas: Soporta programación asincrónica de manera estructurada y secuencial.
- Null Safety: Prevención de errores relacionados con valores nulos en tiempo de compilación.

## Comentarios
Los comentarios en Kotlin se pueden hacer de las siguientes formas:

- Comentarios de una línea con //.
- Comentarios de bloque con /* */.

### Ejemplo:
// Este es un comentario de una línea

/*
   Este es un comentario
   de bloque en Kotlin
*/
