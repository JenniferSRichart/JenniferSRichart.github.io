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
  <summary>Análisis de Datos y Visualización</summary>
  <ul>
    <li>Power BI: modelado de datos, DAX, visualizaciones</li>
    <li>Excel avanzado: Power Query, tablas dinámicas, macros</li>
    <li>Power Automate para flujos de trabajo</li>
    <li>Visualización con Python: Matplotlib, Seaborn, Plotly, Folium, Streamlit</li>
  </ul>
</details>

<details>
  <summary>Programación y Automatización</summary>
  <ul>
    <li>Python (pandas, numpy, scikit-learn, openpyxl)</li>
    <li>SQL (consultas complejas, joins, subconsultas, agregaciones)</li>
    <li>Bash básico</li>
    <li>Web scraping: BeautifulSoup, Selenium</li>
    <li>Consumo de APIs: JSON, XML</li>
  </ul>
</details>

<details>
  <summary>Ciencia de Datos y Machine Learning</summary>
  <ul>
    <li>Modelos supervisados: regresión, clasificación, árboles de decisión, Random Forest</li>
    <li>Modelos no supervisados: K-means, PCA</li>
    <li>Validación cruzada, GridSearchCV</li>
    <li>Procesamiento de lenguaje natural (NLP básico)</li>
    <li>Análisis de series temporales</li>
    <li>Redes neuronales (introducción a CNN y autoencoders)</li>
  </ul>
</details>

<details>
  <summary>Bases de Datos y Nube</summary>
  <ul>
    <li>Gestión y limpieza de datos en SQL Server</li>
    <li>Introducción a entornos cloud: AWS, Azure, Hadoop y Spark</li>
  </ul>
</details>

<details>
  <summary>Herramientas y Entornos de Desarrollo</summary>
  <ul>
    <li>Jupyter Notebooks, PyCharm, Visual Studio Code, Anaconda</li>
    <li>Control de versiones con Git y GitHub</li>
  </ul>
</details>

<details>
  <summary>Idiomas</summary>
  <ul>
    <li>Español: Nativo</li>
    <li>Inglés: Nivel B2 (EOI – Escuela Oficial de Idiomas)</li>
  </ul>
</details>
