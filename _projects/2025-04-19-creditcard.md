---
layout: article
title: "Análisis de Solicitudes de Tarjeta de Crédito"
excerpt: "Dashboard interactivo en Power BI para analizar solicitudes de tarjetas de crédito, entender factores de aprobación y perfilar solicitantes. Proyecto orientado a departamentos de riesgo y marketing bancario."
badges: ["🔵 Estándar"]
cover: /assets/images/proyectos/CreditCard/1.png
readmore: true
---

##  Objetivo del proyecto

Analizar las solicitudes de tarjetas de crédito y comprender los factores que influyen en su aprobación o rechazo. Este análisis permite **optimizar procesos de evaluación de riesgo** y mejorar estrategias de captación de clientes potenciales.

---

##  Vista General del Dashboard

La pestaña principal “Análisis de Solicitudes de Tarjeta de Crédito” presenta indicadores clave:

- Total de solicitudes recibidas.
- Porcentaje de solicitudes aprobadas y denegadas.
- Ingresos familiares medios según el resultado de la solicitud.

También incluye visualizaciones detalladas sobre:

- Relación entre ingresos y tasa de aprobación.
- Impacto de la antigüedad laboral en las decisiones.
- Diferencias de aprobación según el tipo de ocupación.

![Dashboard Principal]({{ '/assets/images/proyectos/CreditCard/1.png' | relative_url }})

---

##  Perfil de Solicitantes Rechazados

Esta vista está centrada en los solicitantes cuya petición fue denegada:

- Total de rechazos.
- Ingresos y antigüedad laboral promedio.
- Distribución por tamaño de unidad familiar, estado laboral y ocupación.
- Comparativa entre personas desempleadas y empleadas.

Permite **detectar perfiles de riesgo** y proponer estrategias de mitigación.

![Dashboard Solicitantes Rechazados]({{ '/assets/images/proyectos/CreditCard/2.png' | relative_url }})

---

##  Dataset y Modelado

Los datos han sido **simulados con fines educativos**. El modelo en Power BI incluye:

- Medidas personalizadas en **DAX**
- Segmentaciones por características demográficas y económicas
- Visualizaciones dinámicas y cruzadas para facilitar la exploración
- Filtros y jerarquías personalizadas

---
