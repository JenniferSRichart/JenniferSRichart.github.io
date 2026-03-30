---
layout: article
title: "Análisis de Engagement y Satisfacción del Cliente – Essenza"
excerpt: "Dashboard en Power BI inspirado en una prueba técnica. Evoluciona hacia un panel corporativo con branding propio, navegación tipo app y versión móvil optimizada para analizar engagement digital, conversión y satisfacción del cliente en una marca ficticia de cosmética."
badges: ["🔵 Estándar", "📱 Móvil", "⭐ Galería Power BI"]
cover: /assets/images/proyectos/Marketing-cosmetic/P1.PNG
readmore: true
---

## Objetivo del proyecto  

Este proyecto nace como la **evolución de una prueba técnica** en la que el dataset original ofrecía muy poca información.  
A partir de esa experiencia decidí darle un enfoque creativo y más completo: inventé la marca ficticia **Essenza**, con identidad visual propia, y diseñé un dashboard que combina métricas de **marketing digital, conversión y satisfacción del cliente**.  

El objetivo es ofrecer a la empresa una visión global que facilite la **toma de decisiones estratégicas**, integrando el comportamiento del cliente en el customer journey, el engagement en redes sociales y las opiniones de los usuarios.  

---

## Dashboard interactivo  

El dashboard está estructurado para responder a las preguntas más frecuentes de la Dirección y de los equipos de marketing y experiencia de cliente:  

- ¿Cuál es el **ratio de conversión** general y cómo evoluciona en el tiempo?  
- ¿Qué impacto tienen las **redes sociales** en visualizaciones, clics y likes?  
- ¿Qué líneas de producto generan mayor **engagement y reputación online**?  
- ¿Cuál es la **percepción global de los clientes** según sus opiniones y valoraciones?  

<button onclick="document.getElementById('pbiframe').style.display='block'; this.style.display='none';" style="padding:10px 20px; background:#0078D7; color:white; border:none; border-radius:6px; cursor:pointer; font-size:16px;">
  ▶ Ver dashboard interactivo
</button>

<div id="pbiframe" style="display:none; margin-top:20px; position:relative; padding-bottom:65%; height:0; overflow:hidden;">
  <iframe 
    title="Cosmetic_Project_PBI-V2" 
    src="https://app.powerbi.com/view?r=eyJrIjoiMGQ4ODk0NDgtYzZiOC00YWU1LWJmZGItODk4MjgwNWJjMjUyIiwidCI6IjY4NTE5ZTQ4LTgzZjMtNDM1Zi1hMzhhLTFhN2FhNzdiYTk4NyIsImMiOjh9" 
    frameborder="0" allowFullScreen="true"
    style="position:absolute; top:0; left:0; width:100%; height:100%;">
  </iframe>
</div>

Una vez dentro del informe, el usuario puede identificar de un vistazo:  

- Los **KPIs principales**: ratio de conversión, interacciones en redes y valoración media de clientes.  
- La **evolución mensual** del funnel de conversión y del sentimiento de los usuarios.  
- El **peso de cada línea de producto** en engagement y reputación online.  
- El detalle de **reseñas y comentarios**, clave para detectar áreas de mejora en experiencia de cliente.  

---

## Usuarios objetivo  

El dashboard está diseñado para ser útil a distintos perfiles dentro de la organización:  

- **Dirección/Gerencia** → visión global y comparativa entre líneas de producto.  
- **Equipo de Marketing Digital** → detalle del rendimiento en redes sociales, clics y campañas.  
- **Atención al Cliente / Customer Experience** → análisis de reseñas y evolución del sentimiento de los clientes.  

De esta manera, un mismo informe responde a las necesidades de varios departamentos, facilitando la toma de decisiones de manera coordinada.  


## Portada (Home)  

El informe arranca con una **portada tipo aplicación** que da acceso al resto de secciones.  
Este enfoque convierte el dashboard en una experiencia más cercana a una **app corporativa**, en lugar de un simple panel de datos.  

Incluye:  
- **Botones interactivos** hacia las páginas de *Panel General, Conversión, Redes Sociales y Opiniones de Clientes*.  
- **Diseño visual coherente** con el branding ficticio de Essenza.  
- Una experiencia de navegación clara y profesional.  

![Home]({{ '/assets/images/proyectos/Marketing-cosmetic/home.png' | relative_url }})

---

## Panel General  

La vista principal funciona como **resumen ejecutivo**. Presenta de un vistazo los indicadores más relevantes del negocio:  

- **Ratio de conversión** general del customer journey.  
- **Engagement en redes sociales**: visualizaciones, clics y likes.  
- **Número total de reseñas** de clientes y evolución de la satisfacción.  
- **Comparativa por línea de producto** para identificar categorías con mejor rendimiento o reputación online.  

Además, esta página incluye **botones de navegación directa** hacia los paneles detallados de *Conversión, Redes Sociales y Opiniones de Clientes*, lo que facilita al usuario pasar del resumen a un análisis en profundidad con un solo clic.  

Este enfoque convierte al Panel General en el **centro de control** del dashboard, pensado para que la dirección identifique rápidamente el estado global del negocio antes de profundizar en cada área.  

![Panel General]({{ '/assets/images/proyectos/Marketing-cosmetic/P1.PNG' | relative_url }})


---

## Conversión  

En esta sección se analiza con más detalle la efectividad del **funnel de conversión**:  

- Evolución mensual del **ratio de conversión**.  
- Número de acciones por etapa del journey: *visualización, clic, compra, abandono*.  
- **Tabla comparativa por producto**, que ayuda a detectar oportunidades de mejora o a destacar los artículos con mejor rendimiento.  

Esta página está orientada a detectar cuellos de botella en el customer journey y apoyar a los equipos de marketing y ventas en la optimización del funnel.  

![Conversión]({{ '/assets/images/proyectos/Marketing-cosmetic/P2.PNG' | relative_url }})

---

## Redes Sociales  

En esta sección se analiza el comportamiento digital de los usuarios en distintos canales.  
Permite a los equipos de marketing evaluar la eficacia de sus campañas y detectar los medios más rentables.  

Incluye:  
- Comparativa de **likes, visualizaciones y clics** a lo largo del año.  
- Distribución de visualizaciones por **canal de origen** (blog, redes sociales, newsletter, vídeo).  
- **Tabla dinámica mensual** con el rendimiento de cada producto en términos de views.  

![Redes Sociales]({{ '/assets/images/proyectos/Marketing-cosmetic/P3.PNG' | relative_url }})

---

## Opiniones de Clientes  

Este apartado se centra en la **satisfacción de los clientes** y en su percepción de los productos.  
El análisis de sentimiento permite anticipar problemas de reputación o reforzar puntos fuertes de la marca.  

Incluye:  
- **Valoración media global** (2,9 sobre 5 en este caso simulado).  
- **Clasificación del sentimiento** de las reseñas (positivo, neutro, negativo).  
- Evolución mensual del sentimiento y **tabla con comentarios recientes** para un análisis más cualitativo.  

![Opiniones]({{ '/assets/images/proyectos/Marketing-cosmetic/P4.PNG' | relative_url }})

---

## Versión móvil  

El dashboard ha sido adaptado también a la vista de **teléfono móvil**, asegurando que pueda consultarse en cualquier momento y lugar.  
La disposición se ha simplificado respecto a la versión de escritorio para priorizar la **lectura ágil en pantallas pequeñas**.  

- Los **filtros principales** aparecen en la parte superior, justo después del título, para que el usuario pueda personalizar la vista desde el inicio.  
- Se incluyen los **KPIs y gráficos esenciales**, reorganizados en formato vertical.  
- No se muestran todas las visualizaciones de la versión de escritorio, sino una selección optimizada que mantiene la coherencia y la utilidad del informe.  

De esta manera, se garantiza una experiencia fluida y práctica, tanto en escritorio como en dispositivos móviles.  

<p align="center">
  <img src="{{ '/assets/images/proyectos/Marketing-cosmetic/App-Essenza.gif' | relative_url }}" 
       alt="Versión Móvil" 
       style="max-width:30%; height:auto;">
</p>




---

## Dataset y Modelado  

Los datos han sido **simulados con fines educativos**, pero el diseño del modelo sigue las prácticas habituales en proyectos profesionales:  

- **Medidas en DAX** para indicadores clave como ratio de conversión, interacciones digitales o satisfacción media.  
- **Segmentadores dinámicos** para filtrar por año, línea de cuidado y producto.  
- **Diseño adaptado a escritorio y móvil**, con navegación tipo aplicación.  

Este enfoque demuestra cómo un dataset sencillo puede transformarse en un **dashboard corporativo atractivo y funcional**, aplicando principios de branding, experiencia de usuario y analítica de negocio.

---

## Publicación  

Este dashboard ha sido publicado en la [**Power BI Data Stories Gallery**](https://community.fabric.microsoft.com/t5/Data-Stories-Gallery/Essenza-Dashboard-de-Engagement-y-Satisfacci%C3%B3n-del-Cliente/td-p/4820550), la galería oficial de la comunidad de Microsoft Power BI.  

---

## Dataset disponible en GitHub  

El dataset utilizado en este proyecto ha sido **diseñado y simulado por mí** con fines educativos.  
Dado el interés que ha generado, he decidido compartir en GitHub una **muestra parcial** del dataset para que pueda descargarse y utilizarse como demo.  

👉 [Acceder al dataset en GitHub](https://github.com/Cristina-MG/Cosmetic-Marketing-Dataset)  





