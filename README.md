# Analisis-de-Datos-Concretera
Este proyecto presenta un sistema de análisis de datos y visualización en Power BI enfocado en la gestión de materiales, costos y eficiencia operativa de una concretera. Se utilizaron herramientas como SQL, Python, Power BI y Excel para modelar, automatizar y presentar datos clave para la toma de decisiones estratégicas.
## 📌 Objetivos del Proyecto

- Monitorear la eficiencia en el consumo de materiales.
- Detectar pérdidas en producción.
- Optimizar el costo unitario por mezcla.
- Automatizar reportes gerenciales.
- Facilitar la toma de decisiones basada en datos.

---

## 🛠 Tecnologías Utilizadas

| Herramienta | Propósito |
|------------|-----------|
| **SQL Server** | Modelado y almacenamiento de datos |
| **Python (Pandas)** | ETL y limpieza de datos |
| **Power BI** | Visualización y análisis interactivo |
| **Excel** | Validación y entrada de datos iniciales |

---

## 🧩 Estructura del Modelo de Datos

- `DIM_FECHAS`: Segmentación temporal y análisis de tendencias.
- `DIM_MATERIALES`: Categorización de insumos.
- `DIM_MEZCLAS`: Cálculo de costos por tipo de mezcla.
- `PERSONAL`: Costos laborales por producción.
- `CLIENTES`: Seguimiento de pedidos y demanda.
- `PRODUCCIÓN`: m³ de concreto producido por fecha y tipo.
- `COSTOS_CEMENTO`: Precio unitario y consumo por tonelada.
- `ENTRADAS_SALIDAS_MATERIALES`: Control de inventarios y pérdidas.

---

## 📊 Dashboards Desarrollados

📊 [**REPORTE GENERAL**]

Reporte ejecutivo quincenal en el cual se muestra un resumen de produccion, inventarios, ganancias y ventas.

📆 [**REPORTE TRIMESTRAL Y SEMANAL**]

Resumen operativo por semana y trimestre.

📊 [**REPORTE DE CONSUMO**]

Reporte operativo y de producción donde se observan la cantidad de concreto producido por mezcla y la cantidad de materiales consumidos.

🧪 [**ANÁLISIS DE PREPARACION DE MEZCLAS**]

Detección de cantidades irregulares de consumo de cemento por mezcla utilizando el algoritmo Isolation Forest.

🧪 [**ANÁLISIS POR REGRESION LINEAL DE MEZCLAS**]

Prediccion de cantidades de insumos para utilizar según el tipo y cantidad de mezcla, detecta mezclas pobres o saturadas de material.



 
## 📈 Resultados Obtenidos
Flujo de entradas y salidas para control de inventario.
- 🔹 Reducción de pérdidas materiales en un **15%**.
- 🔹 Visualización clara de los costos por mezcla y semana.
- 🔹 Automatización de reportes redujo tiempos en un **40%**.
- 🔹 Mejora en la toma de decisiones por parte del equipo directivo.

---
