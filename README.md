# Proyecto Dietas AHP

Este proyecto forma parte del curso **Teoría de la Decisión** y tiene como objetivo aplicar el método **AHP (Analytic Hierarchy Process)** para evaluar diferentes dietas en función de múltiples criterios.

## 📂 Contenido del repositorio

- `Dietas.qmd` — Documento principal en Quarto que describe el análisis paso a paso.  
- `Dietas.html` / `Dietas.pdf` — Resultados renderizados del documento.  
- `dietas_ahp.ahp` — Archivo del modelo AHP.  
- `*.png` — Imágenes y gráficos generados durante el análisis.  
- `Dietas_cache/`, `Dietas_files/` — Carpetas generadas automáticamente por Quarto/R Markdown.  

## 🎯 Objetivo del proyecto

Analizar diferentes dietas considerando criterios como:
- **Costo**
- **Consumo hídrico**
- **Emisiones**
- **Impacto en el suelo**
- **Nutrición**
- **Salud**

Cada criterio fue ponderado utilizando el método AHP, y las alternativas (diferentes dietas) fueron comparadas para obtener una clasificación final.

## ⚙️ Tecnologías utilizadas

- **R** y **Quarto**
- Paquetes: `ahp`, `tidyverse`, `ggplot2`, `knitr`, `rmarkdown`
- Visualización de resultados mediante gráficos `.png` y reportes HTML/PDF.

## 📈 Resultados

El análisis permite determinar cuál de las dietas consideradas presenta un mejor equilibrio global entre costo, impacto ambiental y salud.

## 👩‍💻 Autora

**Camilla Bocciolone**  
Politecnico di Milano — Curso de *Teoría de la Decisión*
