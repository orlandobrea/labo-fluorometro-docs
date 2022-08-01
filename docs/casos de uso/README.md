# casos de uso

`/casos de uso`

* [Overview](../README.md)
  * [archivos de ejemplo](../archivos%20de%20ejemplo/README.md)
  * [**casos de uso**](../casos%20de%20uso/README.md)
  * [diagramas](../diagramas/README.md)

---


![diagram](https://www.plantuml.com/plantuml/svg/0/TPB1JiCm343l-GghzntOTaQJ2kA2j0Ejj1joKwyBX7XoNEs0-7UIigAkKuzsdfzZ9xkeADf_UUFfgA0CuhgJGkk4h3eE1gsoG5777iKnl6B3WYdbk02Cq4UIEVESfAsBwYp6V-YT9bbZiXv3vmcA9ueMfKE12ykdJqW1tmPoLK8NW6IjomVpSsDweK2IiBsq5A0bg0GR_E2PhnHA48-G_a60S4wxS99pPs5bovuZK50XE98zNQUfo_MixrlV40Z5tgSHXnAe3jMiwn8q63SpupZo_IqjXubbOLEmhsv06c--pNtoSy1gzJXiS1Aify76tBtQzMHhp8v2cp_DBm00)

## Generar orden de trabajo

### Basic flow 

| Paso         | Detalle |
|--------------|-----------|
| 1 | El usuario selecciona la fecha desde y hasta de la orden de trabajo a generar |
| 2 | El usuario presiona sobre "Generar Orden de trabajo"|
| 3 | El sistema valida los datos ingresados |
| 4 | El sistema genera la orden de trabajo y le informa al usuario que el proceso fue exitoso mostrando el numero de orden |

### Alternative flow 1

| Paso         | Detalle |
|--------------|-----------|
| 1A1 | Opcionalmente selecciona el protocolo desde y/o hasta |

### Alternative flow 3

| Paso         | Detalle |
|--------------|-----------|
| 3A1 | En caso de error en los datos lo informa al usuario para que los corrija (tambien valida que no existan ordenes de trabajo para las fechas/protocolos indicados)|

## Descargar worklist

### Basic flow 

| Paso         | Detalle |
|--------------|-----------|
| 1 | El usuario selecciona la worklist      |
| 2 | El usuario selecciona el tipo de estudio (laboratorio) |
| 3 | El usuario presiona en "Generar Worklist" |
| 4 | El sistema genera un TXT con la worklist para el estudio indicado y guarda la worklist para futuras referencias |

## Sube resultados en TXT

### Basic flow 

| Paso         | Detalle |
|--------------|-----------|
| 1 | El usuario selecciona la worklist a la cual desea subir los resultados |
| 2 | El usuario presiona sobre seleccionar archivo de resultados en TXT|
| 3 | El usuario selecciona el archivo entregado por el fluorometro con los resultados de las laboratorios |
| 4 | El usuario presiona sobre subir resultados|
| 5 | El sistema valida el archivo y asigna los resultados a la worklist seleccionada |

### Alternative flow 5 - Archivo invalido

| Paso         | Detalle |
|--------------|-----------|
| 5A1 | El archivo es invalido y el sistema informa que debe verificar el archivo seleccionado |

### Alternative flow 5 - El archivo no pertenece a la worklist seleccionada

| Paso         | Detalle |
|--------------|-----------|
| 5A1 | El sistema informa que el archivo no pertenece a la worklist seleccionada |

## Descarga orden de trabajo con resultados

### Basic flow 

| Paso         | Detalle |
|--------------|-----------|
| 1 | El usuario filtra por fecha / numero de OT las ordenes de trabajo |
| 2 | Es sistema muestra las OT que concuerdan con el filtro |
| 3 | El usuario selecciona "Ver resultados" en la OT que quiere ver los resultados |
| 4 | Es sistema muestra los datos de la OT y los resultados de los estudios por pantalla |
| 5 | El usuario presiona sobre el boton Descargar resultados en PDF |
| 6 | El sistema genera y descarga el PDF con los resultados de la OT |


