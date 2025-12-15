# Introducción al Análisis de Datos con R

[![Quarto](https://img.shields.io/badge/Quarto-Website-blue)](https://quarto.org)
[![R](https://img.shields.io/badge/R-4.0+-blue)](https://www.r-project.org/)

Este repositorio contiene todos los materiales para el taller **"Introducción al Análisis de Datos con R"**, diseñado para personas que deseen adquirir las habilidades fundamentales para el análisis de datos utilizando R y RStudio.

## 📋 Contenido del Taller

El curso está organizado en 8 temas principales:

1. **¿R?** - Introducción a R, RStudio y paquetes
2. **Lo Básico de R** - Sintaxis, tipos de datos y estructuras básicas
3. **Importando y Explorando Datos** - Proyectos, importación y exploración inicial
4. **Transformando Datos con dplyr** - Tidyverse y manipulación de datos
5. **La Gramática de los Gráficos con ggplot2** - Creación de visualizaciones básicas
6. **Preprocesamiento de Datos de Encuestas** - Escalas Likert y preparación de datos
7. **Análisis y Visualización de Datos Likert** - Tablas y gráficos especializados
8. **Comunicando sus Resultados con Quarto** - Reportes reproducibles

Cada tema incluye:
- 📊 **Diapositivas** (formato Reveal.js)
- 💻 **Práctica** con ejemplos guiados
- ✏️ **Ejercicios** con soluciones (donde aplique)

## 🚀 Cómo Usar Este Repositorio

### Opción 1: Ver el Sitio Web

El sitio web del curso proporciona acceso a todos los materiales de forma interactiva.

### Opción 2: Clonar y Trabajar Localmente

```bash
git clone https://github.com/juanfonsecaLS1/Intro-a-R.git
cd Intro-a-R
```

Luego abra el proyecto en RStudio haciendo doble clic en `Intro-a-R.Rproj`.

## 📦 Requisitos

### Software Necesario

1. **R** (versión 4.0 o superior): [Descargar aquí](https://cran.r-project.org/)
2. **RStudio** (versión más reciente): [Descargar aquí](https://posit.co/download/rstudio-desktop/)
3. **Quarto** (incluido en RStudio reciente): [Descargar aquí](https://quarto.org/docs/get-started/)

### Paquetes de R

Instale los paquetes necesarios ejecutando:

```r
install.packages(c(
  "tidyverse",    # Colección de paquetes para ciencia de datos
  "readxl",       # Para leer archivos Excel
  "likert",       # Para análisis de escalas Likert
  "sjPlot",       # Para visualización de datos de encuestas
  "quarto"        # Para crear reportes
))
```

## 📁 Estructura del Proyecto

```
Intro-a-R/
├── _quarto.yml           # Configuración del sitio web
├── index.qmd             # Página principal
├── intro_curso.qmd       # Introducción al curso
├── resources.qmd         # Recursos y enlaces
├── materiales/           # Materiales del curso
│   ├── index.qmd        # Página de inicio de materiales
│   ├── tema01/          # ¿R?
│   ├── tema02/          # Lo Básico de R
│   ├── tema03/          # Importando y Explorando Datos
│   ├── tema04/          # Transformando Datos con dplyr
│   ├── tema05/          # La Gramática de los Gráficos con ggplot2
│   ├── tema06/          # Preprocesamiento de Datos de Encuestas
│   ├── tema07/          # Análisis y Visualización de Datos Likert
│   └── tema08/          # Comunicando sus Resultados con Quarto
├── datos/                # Conjuntos de datos de ejemplo
└── images/               # Imágenes y recursos gráficos
```

Cada carpeta de tema contiene:
- `slides.qmd` - Presentación de conceptos
- `practica.qmd` - Ejercicios guiados
- `ejercicios.qmd` - Ejercicios para resolver (donde aplique)
- `index.qmd` - Página de navegación del tema

## 🔨 Generar el Sitio Web Localmente

Para renderizar el sitio web completo:

```bash
quarto render
```

Para previsualizar durante el desarrollo:

```bash
quarto preview
```

El sitio se generará en la carpeta `_site/`.

## 👥 Audiencia

Este taller está dirigido a:

- Investigadores y estudiantes que deseen iniciarse en R
- Personas sin experiencia previa en programación
- Aquellos que necesitan analizar datos de encuestas

**No se requiere** experiencia previa en programación.

## 📖 Licencia

Este material está disponible bajo la licencia GNU General Public License v3.0. Para más detalles, consulte el archivo [LICENSE](LICENSE).

## 📧 Contacto

Para consultas o sugerencias, por favor abra un [Issue](https://github.com/juanfonsecaLS1/Intro-a-R/issues) en este repositorio.

## 🙏 Agradecimientos

Este curso fue desarrollado utilizando:
- [Quarto](https://quarto.org/) para la generación del sitio web
- [Tidyverse](https://www.tidyverse.org/) para los ejemplos de análisis de datos
- [R for Data Science](https://r4ds.hadley.nz/) como referencia principal

---

**¡Bienvenidos al mundo del análisis de datos con R!** 🎉