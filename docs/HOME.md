# Overview

## Sistema de interaccion con fluorometro

#### Caso actual

* Exportan los protocolos en PDF (orden de trabajo) desde un numero y fecha determinado (tomando como base la ultima exportacion en PDF realizada)
* Arman la bandeja (no recuerdo si ese es el nombre) que va al fluorometro para 1 de los 6 estudios que hacen:
   * Cortan una muestra y la ponen en una posicion (hay posiciones para calibracion, dependiendo del tipo de estudio). Se ponen las muestras con prioridad primero
   * Generan un archivo indicando a que paciente corresponde cada posicion (izquierda a derecha, arriba a abajo)
   * Introducen las muestras en el fluorometro
   * El fluorometro entrega los resultados en txt
   * Pasan los resultados manualmente a la orden de trabajo
   * Pasan los resultados manualmente a un excel para graficas
   * Vuelven a repetir estos pasos hasta hacerlo con todos los estudios
* Informan a SIP, el resultado de los estudios (cualitativamente, no cuantititativamente)

![diagram](https://www.plantuml.com/plantuml/svg/0/RP2zRW9138JxVGgNKANdYf0YYbA1GegqvdRGRRAtFja-yVFqB9SW545ZMVRdiSTBSrOV-noc92pUKA2ijDA8GX7qgRpbRo4KLz0ERST6JpIekBIInPgW6C0UY1OlsdEKorZFhkb40oiJpCUOXBwQ_ynUz2SdyrzgbqTHwU4g4_S1pkd4RPBfZZyHguVSeQkjern1XOtPwmgRUcksQkTM9BxpTdL0-ovbqApZustTW19JDGzxdbCocXrXy_18zlNG8ZSFMvltzQO9LIaiQxYy-mm0)

#### Caso deseado

Que el proceso se pueda realizar mas automatizado, dado que manualmente es muy propenso a error

![diagram](https://www.plantuml.com/plantuml/svg/0/RP2zRW9138JxVGgNKANdYf0YYbA1GegqvdRGRRAtFja-yVFqB9SW545ZMVRdiSTBSrOV-noc92pUKA2ijDA8GX7qgRpbRo4KLz0ERST6JpIekBIInPgW6C0UY1OlsdEKorZFhkb40oiJpCUOXBwQ_ynUz2SdyrzgbqTHwU4g4_S1pkd4RPBfZZyHguVSeQkjern1XOtPwmgRUcksQkTM9BxpTdL0-ovbqApZustTW19JDGzxdbCocXrXy_18zlNG8ZSFMvltzQO9LIaiQxYy-mm0)


#### Casos de uso

[Casos de uso](casos_de_uso/HOME)

### Ejemplos

Se pueden ver los ejemplos de entrada/salida del fluorometro y documentos extras en [ejemplos de archivos](archivos%20de%20ejemplo/HOME)
