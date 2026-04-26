---

layout: article
titles:

# @start locale config

en      : \&EN       About
en-GB   : \*EN
en-US   : \*EN
en-CA   : \*EN
en-AU   : \*EN
zh-Hans : \&ZH\_HANS  关于
zh      : \*ZH\_HANS
zh-CN   : \*ZH\_HANS
zh-SG   : \*ZH\_HANS
zh-Hant : \&ZH\_HANT  關於
zh-TW   : \*ZH\_HANT
zh-HK   : \*ZH\_HANT
ko      : \&KO       소개
ko-KR   : \*KO
fr      : \&FR       À propos
fr-BE   : \*FR
fr-CA   : \*FR
fr-CH   : \*FR
fr-FR   : \*FR
fr-LU   : \*FR

# @end locale config

key: page-about
---

<style>
  .about-container {
    display: flex;
    flex-wrap: wrap;
    gap: 2em;
    align-items: flex-start;
  }

  .about-text {
    flex: 1 1 60%;
    min-width: 300px;
  }

  .about-photo {
    flex: 1 1 30%;
    min-width: 200px;
  }

  .about-photo img {
    max-width: 100%;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  }
</style>

<div class="about-container">
  <div class="about-text">
    <p>Hola, soy </strong>Jennifer Sánchez Richart</strong>. Trabajo con datos, pero sobre todo con decisiones. Mi enfoque va más allá del análisis técnico: busco entender el contexto, detectar oportunidades y transformar la información en estrategias que generen impacto real. Me interesa especialmente cómo la tecnología y los datos pueden impulsar cambios sostenibles en organizaciones y personas.</p>
  </div>

  <div class="about-photo">
    <img src="{{ '/assets/images/IMG_1101.png' | relative_url }}" alt="Jennifer Sánchez Richart">
  </div>
</div>

<h3>Certificaciones</h3>

<div style="display:flex; align-items:center; gap:15px; margin-bottom:20px;">
  
  <a href="(https://learn.microsoft.com/en-gb/users/jennifersanchezrichart-1821/credentials/certification/azure-ai-fundamentals?tab=credentials-tab)" target="_blank">
    <img src="{{ '/assets/images/Screenshot 2026-04-26 at 22.45.49.png' | relative_url }}" 
         alt="Microsoft Certified: Azure AI Fundamentals" 
         style="width:90px; height:auto;">
  </a>

  <div>
    <strong>Microsoft Certified: Azure AI Fundamentals</strong><br>
    2025 – La certificación Microsoft Certified: Azure AI Fundamentals (AI-900) valida conocimientos básicos de inteligencia artificial y machine learning aplicados a negocio, junto con los principales servicios de IA en la nube de Azure. Es una certificación introductoria orientada a perfiles no técnicos que buscan entender cómo integrar la IA en la toma de decisiones empresariales.
  </div>

</div>

<style>
  details summary {
    font-weight: bold;
    cursor: pointer;
    margin-top: 1.5em;
    font-size: 1.1em;
  }

  details {
    margin-bottom: 5em;
  }

  details ul {
    margin-top: 0.5em;
  }
</style>

<details>
  <summary>Business Intelligence y Analítica Estratégica</summary>
  <ul>
    <li>Power BI: modelado de datos, DAX y diseño de dashboards orientados a toma de decisiones</li>
    <li>Excel avanzado: Power Query, tablas dinámicas y automatización de procesos</li>
    <li>Transformación de datos en insights accionables para negocio</li>
    <li>Definición de KPIs y storytelling con datos</li>
  </ul>
</details>

<details>
  <summary>Automatización y Gestión de Datos</summary>
  <ul>
    <li>Power Automate: diseño de flujos para optimización de procesos</li>
    <li>SQL: consultas complejas, joins, subconsultas y agregaciones</li>
    <li>Python: manipulación de datos (pandas, numpy) y automatización</li>
    <li>Integración y limpieza de datos de múltiples fuentes</li>
  </ul>
</details>

<details>
  <summary>Análisis Avanzado y Machine Learning</summary>
  <ul>
    <li>Modelos supervisados: regresión, clasificación y árboles de decisión</li>
    <li>Modelos no supervisados: clustering (K-means) y reducción de dimensionalidad (PCA)</li>
    <li>Validación de modelos y optimización básica</li>
    <li>Aplicación de analítica predictiva a problemas de negocio</li>
  </ul>
</details>

<details>
  <summary>IA y Nuevas Tecnologías</summary>
  <ul>
    <li>Fundamentos de Inteligencia Artificial y Machine Learning aplicados a negocio</li>
    <li>Uso de herramientas de IA generativa (ChatGPT, Copilot, etc.)</li>
    <li>Aplicación de IA para automatización, análisis y generación de contenido</li>
  </ul>
</details>

<details>
  <summary>Idiomas</summary>
  <ul>
    <li>Español: Nativo</li>
    <li>Inglés: Nivel C1</li>
  </ul>
</details>
