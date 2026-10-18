# Misión piloto: especificación

Toda la tesis del proyecto depende de una sola cosa: que se pueda demostrar que una acción en el mundo físico ocurrió, sin que sea fácil de falsificar ni carísimo de comprobar.

Mientras eso no se haya hecho una vez de verdad, el resto es documentación. Esta es la especificación de ese primer intento.

## Criterios de la misión piloto

Tiene que ser pequeña, verificable sin ambigüedad y sin consecuencias si falla.

- **Coste**: por debajo de lo que duela perder.
- **Duración**: días, no meses.
- **Evidencia**: inequívoca. Algo donde "¿ocurrió?" tenga una sola respuesta.
- **Sin dependencia de terceros** que puedan retrasarla.
- **Reversible**: si sale mal, nadie queda perjudicado.

Lo que la hace útil no es el impacto, es que el circuito completo se recorra una vez.

## El circuito que hay que probar

1. **Propuesta** — alguien define objetivo, coste y qué contará como evidencia. Esto último se fija *antes* de ejecutar, no después.
2. **Fianza** — ejecutor y verificador depositan garantía. Si actúan de mala fe, la pierden.
3. **Financiación** — con rendimiento donado de forma irreversible.
4. **Ejecución** — el ejecutor hace la acción y presenta la evidencia acordada.
5. **Verificación** — el verificador confirma o rechaza.
6. **Atestación** — el resultado se registra en cadena con EAS.
7. **Liquidación** — se devuelven las fianzas; si hubo disputa, se escala.

## Qué hay que medir

Lo que importa no es si la misión sale bien, sino qué se rompe:

- ¿Cuánto cuesta verificar frente al valor de la misión? Si verificar cuesta más que la acción, el modelo no escala.
- ¿Dónde fue ambigua la evidencia pese a haberla definido antes?
- ¿Cuánto tardó cada paso?
- ¿Qué haría un ejecutor deshonesto en este circuito, y lo detectaríamos?

Esa última es la pregunta de diseño. El piloto sirve sobre todo para responderla con datos en lugar de con suposiciones.

## Resultado esperado

Un informe público con lo que funcionó y, sobre todo, lo que no. Un piloto que descubre tres problemas de diseño es un éxito; uno que sale perfecto probablemente era demasiado fácil para enseñar nada.

> Estado: especificación abierta. La elección de la misión concreta está sin decidir y es un buen punto de entrada para quien quiera contribuir.
