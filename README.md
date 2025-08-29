# Módulo 2: Estadística y Visualización de Datos  
**Diplomado en Ciencia de Datos para la Toma de Decisiones – USS**  
**Profesor:** Francisco Alfaro Medina  
**Horario:** Martes y jueves, 18:30 a 20:30 hrs  
**Modalidad:** Remota  
**Duración:** 4 semanas (8 sesiones)

---

## 🎯 Objetivo General del Módulo

Desarrollar competencias para explorar, analizar e interpretar datos utilizando técnicas estadísticas descriptivas e inferenciales, junto con herramientas modernas de visualización en R. Se espera que el estudiante sea capaz de comunicar hallazgos de manera efectiva a través de reportes reproducibles e interfaces interactivas.

---

## 🔧 Herramientas y librerías utilizadas

- `R`, `RStudio`
- `ggplot2`, `dplyr`, `tidyr`, `skimr`, `GGally`, `corrplot`, `reshape2`, `shiny`, `quarto`, `knitr`, `patchwork`, `readr`
- Datasets sugeridos: `palmerpenguins`, `gapminder`, datos abiertos (`datos.gob.cl`), Kaggle

---

## 📅 Planificación Semanal

### 📘 Semana 1: Visualización Exploratoria y Estadística Descriptiva

**Objetivo:** Explorar los datos a través de visualizaciones efectivas e interpretar medidas estadísticas básicas.

**Contenidos:**
- Fundamentos de visualización con `ggplot2`
  - `geom_histogram`, `geom_boxplot`, `geom_bar`, `geom_point`, `geom_density`
- Estadística descriptiva:
  - Medidas de tendencia central (media, mediana, moda)
  - Medidas de dispersión (desviación estándar, varianza, rango)
  - Medidas de forma (asimetría, curtosis)
- Identificación visual de outliers (boxplots, método IQR)
- Exploración con `skimr` y `GGally` (pair plots)

**Actividad:** Análisis exploratorio individual de un dataset con visualizaciones e interpretación numérica.

---

### 📗 Semana 2: Relaciones entre Variables y Reportes con Quarto

**Objetivo:** Comprender y visualizar relaciones entre variables, e iniciar la generación de reportes reproducibles con Quarto.

**Contenidos:**
- Correlaciones: Pearson, Spearman, Kendall
- `heatmap` de correlación con `ggplot2` + `reshape2`
- Introducción a `Quarto`:
  - Creación de reportes HTML/PDF
  - Estructura de un documento reproducible
  - Integración de texto, código, gráficos e interpretación
- Buenas prácticas para comunicar resultados

**Actividad:** Elaboración de un informe exploratorio con `Quarto`, incluyendo visualizaciones, análisis estadístico e interpretación narrativa.

---

### 📙 Semana 3: Dashboards Interactivos con Shiny

**Objetivo:** Crear interfaces web interactivas que permitan explorar datos de forma dinámica.

**Contenidos:**
- Fundamentos de `Shiny`
  - Inputs: `selectInput`, `sliderInput`, `checkboxInput`
  - Outputs: `plotOutput`, `renderPlot`, `renderText`
- Estructura de una app Shiny (UI + server)
- Ejemplo aplicado: seleccionar variables y generar visualizaciones (histograma, boxplot, gráfico de dispersión)
- Cómo integrar análisis estadísticos simples en apps

**Actividad:** Desarrollo de una mini app `Shiny` para explorar un dataset y presentar insights clave.

---

### 📕 Semana 4: Data Storytelling y Presentación de Proyectos

**Objetivo:** Comunicar de manera efectiva hallazgos analíticos utilizando visualizaciones, narrativa y herramientas interactivas.

**Contenidos:**
- Introducción al **Data Storytelling**
  - Audiencia, mensaje, visualización, narrativa
  - Inspiración en casos reales
- Evaluación de buenas prácticas en storytelling con datos
- Integración de todo lo aprendido: visualización + estadística + narrativa

**Actividad Final:**  
Presentación del proyecto aplicado, en uno de los siguientes formatos:
- Reporte en `Quarto` (HTML o presentación `revealjs`)
- Dashboard en `Shiny`

Evaluación basada en: claridad, coherencia narrativa, uso correcto de visualización, análisis estadístico y creatividad.

---

## 📚 Referencias Sugeridas

- Wickham, H., & Grolemund, G. (2016). *R for Data Science*. O’Reilly. [https://r4ds.hadley.nz/](https://r4ds.hadley.nz/)
- Knaflic, C. N. (2015). *Storytelling with Data: A Data Visualization Guide for Business Professionals*
- Healy, K. (2018). *Data Visualization: A Practical Introduction*. Princeton University Press.
- Chang, W. (2021). *Mastering Shiny*. [https://mastering-shiny.org](https://mastering-shiny.org)
- [https://quarto.org](https://quarto.org): Documentación oficial de Quarto
- [https://shiny.posit.co](https://shiny.posit.co): Recursos para aprender Shiny

---

## ✨ Resultado Esperado

Al finalizar el módulo, el estudiante será capaz de:

- Interpretar y aplicar técnicas estadísticas básicas.
- Utilizar `ggplot2` para visualizar distintos tipos de datos.
- Crear reportes reproducibles con `Quarto`.
- Construir aplicaciones interactivas simples en `Shiny`.
- Comunicar hallazgos de forma clara, visual y narrativa.

