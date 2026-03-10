# Telecom X LATAM - Analisis de churn

Proyecto de analisis exploratorio y limpieza de datos para estudiar la evasion de clientes (churn) en Telecom X LATAM.

## Objetivo

Identificar patrones asociados a la cancelacion del servicio y dejar un notebook claro, ordenado y listo para futuras etapas de modelado predictivo.

## Archivos

- `TelecomX_LATAM.ipynb`: notebook principal con ETL, EDA, graficos e informe final.
- `TelecomX_diccionario.md`: descripcion breve de las variables del dataset.
- `requirements.txt`: dependencias sugeridas para ejecutar el notebook.

## Flujo del analisis

1. Extraccion de datos desde la fuente JSON.
2. Normalizacion de estructuras anidadas a un DataFrame tabular.
3. Limpieza de inconsistencias y creacion de variables utiles.
4. Analisis descriptivo, visualizaciones y conclusiones.

## Hallazgos principales

- La tasa global de churn analizada fue `26.54%`.
- El mayor riesgo aparece en contratos `Month-to-month` (`41.32%`).
- `Electronic check` es el metodo de pago con mas cancelacion (`43.80%`).
- `Fiber optic` concentra un churn alto (`40.56%`).
- Los clientes que cancelan tienen menor antiguedad promedio (`17.98` meses) y mayor cargo mensual promedio (`74.44`).
- La ausencia de `online_security` (`41.77%`) y `tech_support` (`41.64%`) se relaciona con mayor evasion.

## Como ejecutar

1. Crea un entorno virtual de Python 3.10 o superior.
2. Instala las dependencias con `pip install -r requirements.txt`.
3. Abre `TelecomX_LATAM.ipynb` en Jupyter Notebook o Google Colab.
4. Ejecuta las celdas en orden.

## Fuente de datos


- [TelecomX_Data.json](https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json)

