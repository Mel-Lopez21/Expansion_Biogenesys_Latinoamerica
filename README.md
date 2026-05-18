# Estrategia de Expansión Farmacéutica en Latam - Biogenesys Farma

## 📌 Introducción y Objetivo
Este proyecto define la ubicación estratégica óptima para la expansión de la empresa farmacéutica **Biogenesys** en Latinoamérica. 

El objetivo principal fue identificar qué países ofrecen el mejor equilibrio entre **Volumen de Mercado (Oportunidad)** y **Vulnerabilidad Sanitaria (Demanda)**, analizando variables epidemiológicas (COVID-19), demográficas e infraestructura de salud en Argentina, Brasil, Chile, Colombia, México y Perú.

## 🛠️ Stack Tecnológico
* **Python (Pandas, NumPy):** Procesamiento de datos y metodología ETL.
* **Power BI:** Modelado de datos y creación de dashboards interactivos.
* **Estadística:** Análisis de correlaciones entre comorbilidades y mortalidad.

## ⚙️ Metodología (ETL)
Se realizó una limpieza y transformación exhaustiva de datos provenientes de organismos internacionales y el Banco Mundial:
1.  **Extracción:** Datos de evolución de COVID-19 y variables demográficas.
2.  **Transformación:** Manejo de valores nulos, normalización de datos y creación de métricas personalizadas (ej: correlación de enfermedades crónicas).
3.  **Carga:** Integración de Python dentro de Power BI para visualizaciones avanzadas.

## 📊 Visualización de Datos (Dashboards)
Se presentan los hallazgos clave del análisis, realizados en Power BI en la carpeta dashboard:

[Dashboard](./dashboard)

##  Acceso a Datos (Dataset)

Debido a que el dataset maestro contiene más de 12 millones de registros y supera los límites de almacenamiento de GitHub, el archivo original `.csv` se encuentra alojado en un repositorio externo de alta disponibilidad.
Puedes descargar los datos necesarios para replicar este análisis desde el siguiente enlace:

[Descargar Dataset de Biogenesys Farma (CSV)](https://drive.google.com/file/d/18FGvT2x1nqA5TQ22P5FyJ5eLXlHprqzj/view)

##  Conclusión y Recomendación Estratégica

Tras un exhaustivo proceso de análisis que integró variables epidemiológicas, indicadores socioeconómicos (IDH) y la capacidad instalada de infraestructura sanitaria, el proyecto ha logrado identificar con precisión la ubicación geográfica que ofrece el mayor potencial de retorno y sostenibilidad para la expansión de **Biogenesys Farma**.

La decisión final se fundamenta en tres pilares clave detectados durante el estudio:
1. Identificación del territorio con la mayor concentración de demanda regional.
2. Correlación directa entre prevalencia de enfermedades crónicas y necesidad de suministro farmacéutico.
3. Análisis de la densidad poblacional frente a la capacidad de respuesta sanitaria.

Para conocer el país seleccionado y acceder al desglose detallado de los datos, gráficos comparativos y la justificación técnica completa, consulta el informe final en el siguiente enlace:

### [Ver Informe Final y Selección de Ubicación](./informe/README.md)

---
