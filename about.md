<style>
  .about-container {
    display: flex;
    flex-wrap: wrap;
    gap: 2.5em;
    align-items: flex-start;
    margin-bottom: 3em;
  }

  .about-text {
    flex: 1 1 60%;
    min-width: 300px;
  }

  .about-text h1 {
    font-size: 2.6em;
    font-weight: 800;
    margin-bottom: 0.8em;
  }

  .about-text p {
    font-size: 1.05em;
    line-height: 1.75;
    margin-bottom: 1.2em;
  }

  .about-photo {
    flex: 1 1 30%;
    min-width: 220px;
    text-align: center;
  }

  .about-photo img {
    max-width: 280px;
    width: 100%;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.12);
  }

  .certification-card {
    display: flex;
    align-items: center;
    gap: 24px;
    margin-bottom: 28px;
  }

  .certification-card img {
    width: 180px;
    height: auto;
    border-radius: 6px;
  }

  .certification-card strong {
    font-size: 1.1em;
  }

  details summary {
    font-weight: bold;
    cursor: pointer;
    margin-top: 1.5em;
    font-size: 1.1em;
  }

  details {
    margin-bottom: 2em;
  }

  details ul {
    margin-top: 0.5em;
  }
</style>

<div class="about-container">
  <div class="about-text">
    <h1>Jennifer Sánchez Richart</h1>

    <p>Trabajo con datos, pero sobre todo con decisiones. Mi enfoque va más allá del análisis técnico: busco entender el contexto, detectar oportunidades y transformar la información en estrategias que generen impacto real.</p>

    <p>Cuento con experiencia en Business Intelligence, análisis de datos y automatización de procesos, ayudando a convertir información compleja en herramientas claras, útiles y accionables para equipos y organizaciones.</p>

    <p>Me interesa especialmente cómo la inteligencia artificial, la analítica y la tecnología pueden impulsar cambios sostenibles, optimizar procesos y mejorar la toma de decisiones en distintos entornos empresariales.</p>
  </div>

  <div class="about-photo">
    <img src="{{ '/assets/images/IMG_1101.PNG' | relative_url }}" alt="Jennifer Sánchez Richart">
  </div>
</div>

<h3>Certificaciones</h3>

<div class="certification-card">
  <a href="https://learn.microsoft.com/en-gb/users/jennifersanchezrichart-1821/credentials/certification/azure-ai-fundamentals?tab=credentials-tab" target="_blank">
    <img src="{{ '/assets/images/IA_Fundamental_Microsoft.png' | relative_url }}" alt="Azure AI Fundamentals">
  </a>

  <div>
    <strong>Microsoft Certified: Azure AI Fundamentals</strong><br>
    Certificación que valida conocimientos básicos de inteligencia artificial, machine learning y servicios de IA en Azure aplicados a negocio.
  </div>
</div>

<div class="certification-card">
  <a href="#" target="_blank">
    <img src="{{ '/assets/images/PowerBI_Microsoft.png' | relative_url }}" alt="Power BI Data Analyst Associate">
  </a>

  <div>
    <strong>Microsoft Certified: Power BI Data Analyst Associate</strong><br>
    Certificación orientada al análisis de datos con Power BI, incluyendo modelado, visualización y generación de insights para la toma de decisiones.
  </div>
</div>

<details>
  <summary>Business Intelligence y Analítica Estratégica</summary>
  <ul>
    <li>Power BI: modelado de datos, DAX y dashboards orientados a decisiones</li>
    <li>Excel avanzado: Power Query, tablas dinámicas y automatización</li>
    <li>Definición de KPIs y storytelling con datos</li>
  </ul>
</details>

<details>
  <summary>Automatización y Gestión de Datos</summary>
  <ul>
    <li>Power Automate: optimización de procesos</li>
    <li>SQL: consultas complejas, joins y agregaciones</li>
    <li>Python: manipulación de datos y automatización</li>
  </ul>
</details>

<details>
  <summary>Análisis Avanzado y Machine Learning</summary>
  <ul>
    <li>Modelos supervisados y no supervisados</li>
    <li>Clustering y reducción de dimensionalidad</li>
    <li>Analítica predictiva aplicada a negocio</li>
  </ul>
</details>

<details>
  <summary>IA y Nuevas Tecnologías</summary>
  <ul>
    <li>Fundamentos de IA y Machine Learning</li>
    <li>Herramientas de IA generativa (ChatGPT, Copilot, etc.)</li>
    <li>Aplicación de IA en automatización y análisis</li>
  </ul>
</details>

<details>
  <summary>Idiomas</summary>
  <ul>
    <li>Español: Nativo</li>
    <li>Inglés: C1</li>
  </ul>
</details>
