# Datasets para el Curso

Esta carpeta contiene los conjuntos de datos utilizados en los ejemplos y ejercicios del curso.

## Archivos Disponibles

### encuesta_ejemplo.csv
Datos de ejemplo de una encuesta con escalas Likert para los Temas 7 y 8.

**Variables:**
- `id`: Identificador del participante
- `pregunta1` a `pregunta5`: Respuestas en escala Likert (1-5)
- `edad`: Edad del participante
- `genero`: Género del participante

## Cómo Usar

Para cargar los datos en R:

```r
library(readr)

# Asegúrese de estar en un proyecto RStudio
datos <- read_csv("datos/encuesta_ejemplo.csv")
```

## Agregar Sus Propios Datos

Coloque sus archivos de datos (CSV, Excel, etc.) en esta carpeta y use rutas relativas para accederlos desde sus scripts.
