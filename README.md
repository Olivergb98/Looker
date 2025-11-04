# Looker Dashboard Project

Este proyecto tiene como objetivo explorar el uso de **Looker Studio** para la creación de dashboards a partir de datos generados artificialmente. El flujo de trabajo incluyó la generación de un dataset simulado con Python, su limpieza y posterior análisis visual en Looker.

👉 [Link al dashboard interactivo]()

---

## 📊 Objetivo del proyecto

Aprender a:

* Generar un conjunto de datos sintético para pruebas de visualización.
* Importar y transformar datos en **Looker Studio**.
* Crear un dashboard con métricas clave de marketing digital.

---

## 🧩 Generación del dataset

El dataset se creó mediante un script en Python utilizando las librerías `pandas`, `numpy`, y `random`.
Se generaron **2,500 registros** que simulan métricas de campañas publicitarias en distintos canales, fuentes y campañas.

**Variables principales:**

* `Date`: Fecha de la observación (2023–2024)
* `Channel`: Canal de marketing (Programmatic, Paid Search, Paid Social, Organic)
* `Data Source`: Fuente del tráfico (Google, LinkedIn, Facebook, etc.)
* `Campaign`: Nombre de la campaña
* `Spend`: Gasto total
* `CTR`, `CPC`, `CPM`: Indicadores de rendimiento publicitario
* `Impressions`, `Video Views`, `Conversions`, `Conversion Rate`

El código completo se encuentra en el notebook del proyecto:
`data_generator.ipynb`

---

## 📈 Dashboard en Looker

El dataset fue cargado en **Looker Studio** para crear un dashboard interactivo con métricas clave de rendimiento.

**Métricas destacadas (2024):**

* **Spend total:** $45.38M
* **CTR promedio:** 3.4%
* **Impressions:** 614.5M
* **Video Views:** 306.9M
* **Conversions:** 8.9M
* **Conversion Rate:** 64.1K

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

## 📁 Estructura del proyecto

```
├── data_generator.ipynb       # Script de generación de datos
├── Test_Dashboard.pdf          # Reporte final exportado desde Looker
├── README.md                   # Descripción del proyecto
```

