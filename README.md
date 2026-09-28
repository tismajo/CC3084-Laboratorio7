# Laboratorio 7 — Spark MLlib (CC3066 Data Science)

Análisis de salarios de personas asalariadas con las bases de Personas de la ENEIC (INE Guatemala),
usando PySpark 3.5 y `pyspark.ml`.

## Integrantes

- María José Girón Isidro ([@tismajo](https://github.com/tismajo))
- Leonardo Dufrey Mejía Mejía ([@dufreyM](https://github.com/dufreyM))
- Mia Alejandra Fuentes Mérida ([@miafuentes30](https://github.com/miafuentes30))

## Contenido

`Laboratorio7.ipynb` incluye:

1. Carga, armonización y calidad de datos (Excel → Spark → Parquet, `unionByName`, filtros auditados)
2. Estadística descriptiva
3. Correlaciones (`Correlation.corr`)
4. Segmentación con KMeans (K = 2–5)
5. Pipeline de regresión lineal
6. Pipeline de Random Forest
7. Entrenamiento final (2025) y evaluación en 2026T1
8. Análisis de errores y discusión final

## Cómo ejecutar

1. Descargar las bases de Personas de la ENEIC (I–IV 2025 y I 2026) desde
   <https://www.ine.gob.gt/encuesta-nacional-de-empleo-e-ingresos/> y colocarlas en `./data/`
   con los nombres que aparecen en la celda `ARCHIVOS` del notebook.
2. Usar Python 3.11 con PySpark 3.5.x, pandas, openpyxl, matplotlib y seaborn.
3. Ejecutar el notebook de principio a fin. Crea `./data/parquet/` y `./modelos/`.

Los datos y los modelos no se versionan porque son muy pesados (ver `.gitignore`).
