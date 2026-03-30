---
layout: article
title: "Monitorización de la Fidelidad de los Clientes"
excerpt: "Aplicación desarrollada con R y Shiny para monitorizar la fidelidad de clientes bancarios mediante dashboards, segmentación avanzada y modelos predictivos de churn."
badges: ["🔵 Estándar"]
cover: /assets/images/proyectos/Fidelización/CapturaFidelizacionHome.png
readmore: true
---

##  Objetivo del proyecto

Evaluar y visualizar el grado de fidelidad de clientes bancarios mediante un enfoque de análisis segmentado y predictivo. El objetivo es **anticipar posibles bajas y reforzar la retención de clientes**.

---

##  Overview

La pestaña principal muestra un dashboard con visualizaciones clave:

- Estado general de la fidelización por país.
- Distribución por edad y solvencia financiera.
- Gráficos comparativos entre clientes fidelizados y no fidelizados.

Una vista general útil para **detectar patrones de comportamiento** y áreas de mejora.

![Overview]({{ '/assets/images/proyectos/Fidelización/Fidelizacion_1.png' | relative_url }})

---

##  Análisis de Segmentos de Clientes

Se aplica un modelo de **K-means clustering** para agrupar a los clientes en cuatro segmentos:

- Celestial Customer
- Esmerald Customer
- Purple Customer
- Golden Customer

Para cada grupo se presentan características principales y gráficos que reflejan su fidelidad y comportamiento.

![Segmentos]({{ '/assets/images/proyectos/Fidelización/Fidelizacion_2.png' | relative_url }})

---

##  Predicción de Fidelidad

En esta sección se aplica un modelo predictivo de **árbol de decisión**. El usuario puede introducir parámetros como ingresos, edad y país, y obtener la **probabilidad de fidelización** de un cliente.

Herramienta muy útil para departamentos de CRM y fidelización.

![Predicción]({{ '/assets/images/proyectos/Fidelización/Fidelizacion_3.png' | relative_url }})

---

##  Dataset y Modelado

Los datos han sido **simulados con fines educativos**. La aplicación ha sido desarrollada íntegramente en R con los siguientes elementos:

- Shiny para interfaz interactiva
- Clustering con `kmeans()`
- Modelado predictivo con `rpart`
- Visualizaciones con `ggplot2` y `plotly`

Puedes consultar el **código fuente y documentación** en el repositorio de GitHub.

---
