# Analisis-Datos-2 — Plantilla de Análisis Exploratorio de Datos

Notebook reutilizable para análisis exploratorio de datos (EDA) genérico: carga un CSV, aplica limpieza básica (duplicados, nulos, filtrado de columnas) y genera visualizaciones estándar (gráfico de barras, scatter plot, box plot) más un reporte automático con `pandas_profiling`.

Para usarlo con un dataset propio alcanza con reemplazar `'data.csv'` por el archivo a analizar y ajustar los nombres de columnas (`column_name`, `column_name1`, `column_name2`) marcados como placeholders en el notebook.

## Contenido

- `analisis_datos.ipynb` — plantilla de EDA con limpieza, visualización y profiling automático.

## Tecnologías

Python · pandas · seaborn · matplotlib · pandas-profiling

## Cómo ejecutar

```bash
pip install pandas numpy matplotlib seaborn pandas-profiling jupyter
jupyter notebook analisis_datos.ipynb
```

## Autor

Horacio Laphitz — [GitHub](https://github.com/HoracioLaphitz) · [LinkedIn](https://www.linkedin.com/in/horacio-laphitz)
