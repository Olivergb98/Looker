# Looker Dashboard Project

EExploración de Looker Studio para crear un dashboard interactivo de marketing digital a partir de datos generados sintéticamente con Python.
El proyecto demuestra el flujo completo desde la generación de un dataset hasta la visualización dinámica de métricas clave.


Link al dashboard interactivo:

https://lookerstudio.google.com/reporting/6ec60200-6689-4dbe-942a-c02bb731ceb4/page/vhRZF

---

## 📊 Objetivo del proyecto

Aprender a:

* Generar un conjunto de datos sintético para pruebas de visualización.
* Importar y transformar datos en **Looker Studio**.
* Diseñar un dashboard con indicadores clave de rendimiento (KPIs) y segmentaciones interactivas.

---

## 🧩 Generación del dataset

El dataset se creó mediante un script en Python utilizando las librerías pandas, numpy, y random, con una semilla fija para reproducibilidad.
Se generaron 2,500 registros que simulan campañas publicitarias en diferentes canales y plataformas.

**Variables principales:**

* `Date`: Fecha de la observación (2023–2024)
* `Channel`: Canal de marketing (Programmatic, Paid Search, Paid Social, Organic)
* `Data Source`: Fuente del tráfico (Google, LinkedIn, Facebook, etc.)
* `Campaign`: Nombre de la campaña
* `Spend`: Gasto total
* `CTR`, `CPC`, `CPM`: Indicadores de rendimiento publicitario
* `Impressions`, `Video Views`, `Conversions`, `Conversion Rate`

El código completo se encuentra en el notebook del proyecto:
`Dataset_generator.ipynb`

---

## 📈 Dashboard en Looker

El dataset fue cargado en **Looker Studio** para crear un dashboard interactivo con métricas clave de rendimiento.

**Métricas destacadas (2024):**

* **Spend total:** $42.3M
* **CTR promedio:** 3.4%
* **CPC promedio:** $3.2
* **Impressions:** 612.1M
* **Video Views:** 310.9M
* **Conversions:** 8.3M
* **Conversion Rate:** 60.8K

**Principales visualizaciones:**

* Evolución mensual del gasto publicitario.
* Rendimiento por canal (`Paid Search`, `Paid Social`, `Programmatic`, `Organic`).
* Comparativa de fuentes de datos (`Google`, `Facebook`, `LinkedIn`, etc.).
* Resultados por campaña.

📄 *Consulta el reporte completo en el archivo:*
[`Test_Dashboard.pdf`](./Test_Dashboard.pdf)

---

## 🚀 Aprendizajes

Este proyecto me permitió:

* Comprender el flujo de trabajo completo entre **Python (para generación de datos)** y **Looker Studio (para visualización)**.
* Practicar el diseño de dashboards enfocados en métricas de marketing.
* Reforzar habilidades en análisis exploratorio y visual storytelling con datos.

---

## 🛠️ Tecnologías utilizadas

* **Python** (pandas, numpy, random)
* **Looker Studio**
* **Jupyter Notebook**

---

