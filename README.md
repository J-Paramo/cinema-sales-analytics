# Cinema Sales Analytics

Proyecto de análisis de datos e inteligencia de negocios enfocado en el desempeño operativo de complejos cinematográficos.  
El objetivo es transformar datos de ventas en insights accionables mediante Python y Power BI.

---

## Resumen del proyecto

Este proyecto analiza el comportamiento de ventas, ocupación y rendimiento operativo de distintos cines a lo largo del tiempo.

Se utilizan técnicas de limpieza de datos, análisis exploratorio (EDA) y visualización en Power BI para identificar patrones de consumo y optimizar la toma de decisiones.

---

## Objetivo

Desarrollar un dashboard interactivo en Power BI que permita:

- Analizar ingresos por cine y película
- Identificar patrones de ventas por día y mes
- Evaluar la ocupación de salas
- Detectar horarios y periodos de mayor demanda
- Optimizar decisiones operativas basadas en datos

---

## Preguntas de negocio

- ¿Qué cines generan mayores ingresos?
- ¿Qué películas tienen mejor desempeño?
- ¿Qué días de la semana son más rentables?
- ¿Existen patrones de estacionalidad en las ventas?
- ¿Cómo varía la ocupación de las salas?
- ¿Qué relación existe entre precio del ticket y ventas?

---

## Procesamiento de datos

Se realizó un proceso de limpieza y transformación de datos que incluyó:

### Limpieza de datos
- Eliminación de valores nulos en variables críticas
- Validación de consistencia en registros
- Conversión de valores tipo date 

### Validación de integridad de datos
Se verificó la coherencia entre ventas reportadas y ventas calculadas

---

## EDA (Exploratory Data Analysis)

Se realizó un análisis exploratorio de los datos (EDA) con el objetivo de identificar insights de comportamiento en las ventas, ocupación y rendimiento operativo de los cines.

### Análisis temporal
- Se identificaron patrones de estacionalidad en las ventas por mes y por día de la semana.
- Se observó que ciertos meses presentan mayor volumen de ventas, indicando posibles periodos de alta demanda.
- El análisis diario mostró variaciones significativas en el comportamiento de ventas a lo largo del tiempo.

### Análisis de desempeño
- Se analizaron los ingresos por cine, identificando diferencias significativas entre complejos.
- Se evaluó el rendimiento de las películas en función de sus ingresos totales.

### Ocupación de salas
- Se estudió la variación de la ocupación promedio por mes.
- Se identificaron cambios en la eficiencia de uso de las salas a lo largo del periodo analizado.

### Relación entre variables
- Se analizó la relación entre el precio del ticket y las ventas totales.
- Se exploró la distribución de ventas por rangos de precio.

### Hallazgos importantes
- Se detectaron diferencias significativas en el rendimiento entre cines y películas.
- Se identificaron patrones de demanda relacionados con el tiempo (meses y días).
- Se observa una variación en las ventas promedio según rangos de precio del ticket. Sin embargo, esta relación no implica causalidad directa, ya que puede estar influenciada por otros factores como la demanda de películas o el tamaño del cine.

---

El EDA permitió establecer una base sólida para la construcción del dashboard en Power BI.

---

## Power BI Dashboard

Se desarrolló un dashboard interactivo en Power BI para la visualización y análisis del desempeño de los cines.

KPIs principales
- Ventas totales
- Unidades vendidas
- Venta promedio
- Ventas por día
Visualizaciones incluidas
- Ventas por día (tendencia temporal)
- Ventas por cine (comparativo de desempeño)
- Ventas por película (ranking de rendimiento)
  
### Objetivo del dashboard

Permitir un análisis rápido del comportamiento de ventas, identificar patrones de demanda y comparar el desempeño entre cines y películas para apoyar la toma de decisiones.

## Herramientas utilizadas

- Python (Pandas, NumPy, Seaborn, Pyarrow, Matplotlib)
- Jupyter Notebook

---

### Estado actual

- Data Cleaning ✔
- Feature Engineering ✔
- Data Validation ✔
- EDA en progreso ✔
- Power BI Dashboard en procesos

## Dataset

Fuente: Kaggle - Cinema Tickets

