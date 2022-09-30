# Mis apuntes extra sobre Modelo del Dominio

* Conjunto de clases conceptuales significativas del mundo real, no de componentes de software.
* Fuente de inspiración para el diseño de los objetos software.
* No son diagramas de clases u objetos de software con responsabilidades.

## Modelos del dominio

Modelo del dominio = Objetos + Atributos + Asociaciones

Modelo del dominio: diccionario visual de abstracciones

Modelo del dominio no son componentes de software: no ventanas, no BBDD, no responsabilidades (de software), no métodos.

### Clase conceptual

- Informalmente: una idea, una cosa o un objeto.
- Formalmente: Se puede considerar en términos de su símbolo, intensión y extensión [MO95]
  - Símbolo: palabras que representan una clase conceptual.
  - Intensión: definición de la clase conceptual.
  - Extensión: ejemplos a los que se aplica la clase.

### Descomposición

- Divide y vencerás
- En análisis estructurado: dividimos por funciones
- En análisis II, dividimos por cosas o entidades.

> La principal tarea del análisis es identificar diferentes conceptos en el dominio del problema y documentar el resultado en un modelo del dominio.

### Somos iterativos

- El modelo del dominio se construye incrementalmente a lo largo de varias iteraciones en la fase de elaboración.

> Es mejor especificar en exceso un modelo del dominio con muchas clases conceptuales de grano fino que especificar por defecto.

- Es normal obviar clases y descubrirlas más tarde.

### No existe una lista "correcta"

- Puesto que es una colección algo arbitraria de abstracciones que el modelador considera relevantes.

## Guía

### Cómo hacerlo

1. Liste clases conceptuales candidatas.
1. Represéntelos en un diagrama
1. Asocie
1. Añada atributos

