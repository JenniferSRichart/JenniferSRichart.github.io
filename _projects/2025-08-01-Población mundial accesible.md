---
layout: article
title: "Dashboard de Demografía Mundial 1950–2023"
badges: ["🔵 Estándar", "🟡 Accesible"]

excerpt: "Dashboard interactivo en Power BI que analiza la evolución de la población mundial, su estructura por edades y la relación de dependencia. Incluye versión accesible con alto contraste, simulación en vídeo de distintos tipos de visión y motivación personal hacia la accesibilidad."

cover: /assets/images/proyectos/Demografia/P1.png
readmore: true
---

## Objetivo del proyecto

El objetivo de este proyecto es **analizar la evolución de la población mundial entre 1950 y 2023**, poniendo especial énfasis en la distribución por franjas de edad y en la **relación de dependencia** (población activa frente a dependientes).  

Además, se incorpora una **versión accesible del dashboard**, optimizada en cuanto a contraste de colores y tipografía, junto con una simulación en vídeo que muestra cómo lo perciben personas con distintos problemas de visión.  
Este enfoque busca reflejar **buenas prácticas de accesibilidad** en proyectos de análisis de datos.  

---

## Dashboard interactivo

El dashboard responde a las siguientes preguntas clave:  
- ¿Cómo ha crecido la población mundial desde 1950?  
- ¿Cuál es la proporción de menores de 15, adultos en edad de trabajar y mayores de 65?  
- ¿Qué países concentran mayor población en la actualidad?  
- ¿Cómo ha evolucionado la relación de dependencia a lo largo del tiempo?  

<button onclick="document.getElementById('pbiframe').style.display='block'; this.style.display='none';" style="padding:10px 20px; background:#0078D7; color:white; border:none; border-radius:6px; cursor:pointer; font-size:16px;">
  ▶ Ver dashboard interactivo
</button>

<div id="pbiframe" style="display:none; margin-top:20px; position:relative; padding-bottom:65%; height:0; overflow:hidden;">
  <iframe 
    title="Población mundial - Accesible" 
    src="https://app.powerbi.com/view?r=eyJrIjoiNTA3NGZhOWMtYTliZC00ZjA1LTgxN2EtODY5ZDAwYjMzOWM2IiwidCI6IjY4NTE5ZTQ4LTgzZjMtNDM1Zi1hMzhhLTFhN2FhNzdiYTk4NyIsImMiOjh9" 
    frameborder="0" allowFullScreen="true"
    style="position:absolute; top:0; left:0; width:100%; height:100%;">
  </iframe>
</div>


Dentro del informe se pueden explorar distintos aspectos:  
- **KPIs globales** del año seleccionado: población total, variación respecto al año anterior, menores de 15, mayores de 65 y relación de dependencia.  
- **Evolución histórica de la población mundial (1950–2023)**, diferenciada por franjas de edad.  
- **Mapa interactivo de población por país**, que refleja la distribución geográfica en el año seleccionado.  
- **Ranking dinámico** con los 5 países más poblados en cada año.  

---

## Versión estándar y accesible

El dashboard se diseñó en dos versiones:  
- **Versión estándar**, con estilo neutro y visualización clara.  
- **Versión accesible**, optimizada para distintos tipos de daltonismo y con un contraste mínimo de 4.5:1, siguiendo las recomendaciones de las **WCAG 2.1**.  

📊 **Vista estándar**  
![Versión Estándar]({{ '/assets/images/proyectos/Demografia/P1.png' | relative_url }})

🌍 **Vista accesible**  
![Versión Accesible]({{ '/assets/images/proyectos/Demografia/P2.png' | relative_url }})

---

## Simulación de problemas de visión

Se incluye un **vídeo explicativo** donde se muestra cómo perciben el dashboard personas con diferentes condiciones visuales (protanopia, deuteranopia, tritanopia y monocromatismo).  

Aunque la grabación es de una página web y la calidad no es máxima, ilustra de forma clara cómo un diseño inadecuado puede dificultar la lectura de un informe.  

![Simulación Accesible]({{ '/assets/images/proyectos/Demografia/muestra.gif' | relative_url }})

---

## Motivación personal

La motivación de este enfoque inclusivo surge también de una **experiencia personal**: un compañero con daltonismo me explicó las dificultades que encontraba al interpretar dashboards con paletas mal diseñadas.  
Esto me impulsó a validar el informe con **simulaciones de accesibilidad visual**, para asegurar que la información fuese clara y comprensible para todos los usuarios.  

---

## Dataset y Modelado

Los datos provienen de la base de datos de **United Nations World Population Prospects**, que ofrece series históricas de población mundial por país, continente, año y grupos de edad.  

El modelado se realizó en Power BI con las siguientes prácticas:  
- **Medidas en DAX** para KPIs clave: población total, variación interanual, población por franjas de edad y relación de dependencia.  
- **Segmentador interactivo** por año.  
- Diseño en dos versiones: **estándar** y **accesible**.  

Este enfoque permite no solo analizar tendencias globales, sino también demostrar cómo integrar **buenas prácticas de accesibilidad** en un dashboard real.  
