# Analisis-Datos-2 — Plantilla de Análisis Exploratorio de Datos

## Descripción

Notebook reutilizable para análisis exploratorio de datos (EDA) genérico: carga un CSV, aplica limpieza básica (duplicados, nulos, filtrado de columnas) y genera visualizaciones estándar (gráfico de barras, scatter plot, box plot) más un reporte automático con `pandas_profiling`.

## Contenido

- `analisis_datos.ipynb` — plantilla de EDA con limpieza, visualización y profiling automático.

## Diagrama

[Explorar la arquitectura interactiva en GitDiagram](https://gitdiagram.com/HoracioLaphitz/Analisis-Datos-2)

```mermaid
flowchart LR
  A["analisis_datos.ipynb"] --> B["Procesamiento de Analisis-Datos-2"]
  B --> C["Resultados del proyecto"]
```

## Tecnologías

Python · pandas · seaborn · matplotlib · pandas-profiling

## Cómo ejecutar

```bash
pip install pandas numpy matplotlib seaborn pandas-profiling jupyter
jupyter notebook analisis_datos.ipynb
```

## Autor

Horacio Laphitz — [GitHub](https://github.com/HoracioLaphitz) · [LinkedIn](https://www.linkedin.com/in/horacio-laphitz)
