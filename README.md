# Customer Data Cleaning and Wrangling

## Descripción del proyecto

Este proyecto corresponde al desarrollo de un flujo completo de preparación de datos, que abarca desde la generación e integración de múltiples fuentes hasta la obtención de un dataset final limpio, estructurado y listo para análisis.

El trabajo fue desarrollado como parte del Módulo 4 – Preparación de Datos, y se encuentra orientado a aplicar buenas prácticas de limpieza, transformación y organización de datos utilizando Python.

---

## Objetivo

El objetivo del proyecto es construir un dataset confiable y reutilizable a partir de datos con problemas de calidad, aplicando técnicas de imputación, detección de outliers y *data wrangling*, de manera reproducible y documentada.

---

## Justificación del uso de NumPy y Pandas

- **NumPy** se utilizó para la generación de datos ficticios reproducibles y para operaciones numéricas eficientes sobre arreglos.
- **Pandas** se empleó como herramienta principal para el manejo de datos tabulares, limpieza, transformación, categorización y análisis mediante agrupamientos.

Estas librerías constituyen el estándar en el ecosistema Python para análisis y preparación de datos.

---

## Descripción del dataset y fuentes de datos

El proyecto trabaja con un dataset ficticio de clientes y transacciones, generado de forma controlada para simular un escenario realista de comercio electrónico.

Adicionalmente, se incorporó información externa de referencia obtenida desde fuentes oficiales, la cual fue integrada al flujo de trabajo para enriquecer el análisis.

La generación de los datos se realizó utilizando una semilla fija, garantizando la reproducibilidad del proceso.

---

## Técnicas de limpieza y transformación aplicadas

Durante el desarrollo del proyecto se aplicaron las siguientes técnicas:

- Identificación y tratamiento de valores nulos mediante imputación.
- Detección y tratamiento de valores atípicos utilizando el criterio del rango intercuartílico (IQR).
- Creación de variables derivadas relevantes para el análisis.
- Categorización de clientes según niveles de compras y gasto.
- Agrupamientos y generación de tablas resumen por segmento.

---

## Principales decisiones y desafíos

Entre las principales decisiones del proyecto se encuentran la elección de criterios estadísticos estándar para el tratamiento de outliers y la priorización de técnicas que permiten preservar la mayor cantidad de información posible.

Uno de los principales desafíos fue equilibrar la limpieza de los datos con la conservación de registros relevantes, evitando eliminar observaciones de forma innecesaria.

---

## Resultados y estado final del dataset

Como resultado del proceso, se obtuvo un dataset final limpio y enriquecido, exportado en formatos CSV y Excel, listo para su uso en análisis descriptivos, visualización o modelado.

Además, se generaron tablas resumen que permiten analizar el comportamiento de los clientes por distintos segmentos.

---

## Archivos principales del repositorio

- `customer_data_cleaning_wrangling.ipynb`: Notebook con el desarrollo completo del proyecto.
- `clientes_final_wrangle.csv`: Dataset final limpio y estructurado.
- `clientes_final_wrangle.xlsx`: Dataset final en formato Excel.

---

## Tecnologías utilizadas

- Python
- NumPy
- Pandas
- Jupyter Notebook
