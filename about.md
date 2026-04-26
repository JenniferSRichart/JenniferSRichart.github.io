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

<h3>Formación</h3>

<style>
  .education-section {
    margin-top: 1em;
  }

  .education-year {
    font-weight: 700;
    font-size: 1.2em;
    margin-top: 1.5em;
  }

  .education-list {
    margin-top: 0.5em;
    padding-left: 1.2em;
  }

  .education-list li {
    margin-bottom: 0.8em;
    line-height: 1.5;
  }

  .education-list small {
    color: #555;
  }
</style>

<div class="education-section">

  <div class="education-year">2026</div>
  <ul class="education-list">
    <li>
      Creación, interpretación y comunicación de cuadros de mando con Tableau
    </li>
  </ul>

  <div class="education-year">2025</div>
  <ul class="education-list">
    <li>
      PL-200: Consultor de Power Platform – Experis Academy (Manpower Group)
      <br><small>Diseño de soluciones empresariales, automatización de procesos y uso de Power Apps, Power Automate y Dataverse</small>
    </li>
  </ul>

  <div class="education-year">2024</div>
  <ul class="education-list">
    <li>
      Máster Online en IA e Innovación – Founderz  
      <br><small>Formación en machine learning, IA generativa y aplicación en negocio</small>
    </li>
    <li>
      Python con Power BI – Temixa
    </li>
    <li>
      Desarrollo de Chatbots con Azure OpenAI – Platzi
    </li>
    <li>
      Describir cómo crear aplicaciones con Microsoft Power Apps – Microsoft Learn
    </li>
    <li>
      Describir el valor empresarial de Microsoft Power Platform – Microsoft Learn
    </li>
    <li>
      Identificar los componentes fundamentales de Microsoft Power Platform – Microsoft Learn
    </li>
    <li>
      Describe the AI authoring experience in Power Platform – Microsoft Learn
    </li>
    <li>
      PL-900: Microsoft Power Platform Fundamentals – Microsoft Learn
    </li>
  </ul>

</div>

<h3>Últimos eventos asistidos</h3>

<style>
  .events-section {
    margin-top: 1em;
  }

  .event-item {
    margin-bottom: 0.8em;
    line-height: 1.6;
  }

  .event-item strong {
    font-weight: 600;
  }

  .event-year {
    color: #777;
    margin-left: 6px;
  }
</style>

<div class="events-section">

  <div class="event-item">
    <strong>Data Saturdays Madrid</strong> <span class="event-year">2025</span>
  </div>

  <div class="event-item">
    <strong>3ª Edición Expansión IA y Nuevas Tecnologías</strong> <span class="event-year">2025</span>
  </div>

  <div class="event-item">
    <strong>Tech Show Madrid</strong> <span class="event-year">2025</span>
  </div>

  <div class="event-item">
    <strong>VIII Jornada Juntas Contra el Cáncer – HM CIOCC</strong> <span class="event-year">2025</span>
  </div>

  <div class="event-item">
    <strong>II Levin Summer Summit Madrid</strong> <span class="event-year">2025</span>
  </div>

  <div class="event-item">
    <strong>La Brújula de la Competitividad Europea y su Impacto en el Ecosistema de Salud Español</strong> <span class="event-year">2025</span>
  </div>

</div>
