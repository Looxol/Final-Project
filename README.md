# Final-Project

Este proyecto ha sido desarrollado como parte de la asignatura **Visualización de Datos** del **Máster de Ciencia de Datos de la Universitat Oberta de Catalunya (UOC)**.

El objetivo es crear una visualización interactiva y comprensible que ayude a personas —especialmente desde España— a comparar la calidad de vida en distintos países y a lo largo del tiempo, con el fin de tomar decisiones más informadas sobre migración internacional.

---

## 📊 Datos

Los datos provienen de la plataforma [Our World in Data](https://ourworldindata.org/), y se han utilizado métricas relacionadas con salud, economía, trabajo, coste de vida y bienestar subjetivo.

---

## 🧮 Índice Compuesto de Calidad de Vida (ICCV)

Se ha diseñado una métrica sintética llamada **ICCV** (*Índice Compuesto de Calidad de Vida*) que permite clasificar los países de forma objetiva. La fórmula utilizada es:
ICCV = 0.25E + 0.10H + 0.25I - 0.10U - 0.05W - 0.05C - 0.10L + 0.10K

Donde:

| Variable | Descripción |
|----------|-------------|
| **E** | Esperanza de vida |
| **H** | Gasto sanitario per cápita |
| **I** | Ingreso medio después de impuestos |
| **U** | Tasa de desempleo |
| **W** | Horas de trabajo anuales |
| **C** | Índice de precios al consumidor (CPI) |
| **L** | Índice de desigualdad económica (Gini) |
| **K** | Índice de felicidad (Cantril Ladder) |

> Todos los valores han sido normalizados para estar entre 0 y 1, y ponderados según su relevancia para el bienestar general.

---

## 📈 Visualización

Se ha generado una visualización animada tipo **Bar Race**, que muestra la evolución del ICCV en distintos países a lo largo del tiempo. Esto permite:

- Identificar qué países mejoran o empeoran en calidad de vida.
- Comparar tendencias entre regiones o continentes.
- Detectar oportunidades migratorias basadas en datos objetivos.

Puedes ver la visualización interactiva del índice ICCV en el siguiente enlace:

👉 [Ver gráfico en Flourish](https://public.flourish.studio/visualisation/23637072/)
