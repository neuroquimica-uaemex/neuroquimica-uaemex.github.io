---
layout: default
title: Inicio
---

<link rel="stylesheet" href="{{ '/assets/css/lab.css' | relative_url }}">

<section class="hero-lab">
  <div class="hero-content">
    <img src="{{ '/images/uaemex_logo.png' | relative_url }}" alt="Logo UAEMex" class="hero-logo">

    <p class="eyebrow">Universidad Autónoma del Estado de México</p>
    <h1>Laboratorio de Neuroquímica</h1>
    <p class="hero-subtitle">
      Investigación en neuroquímica, biología celular y mecanismos moleculares asociados a cáncer,
      glioblastoma, muerte celular y agotamiento inmunológico.
    </p>

    <nav class="hero-nav">
      <a href="{{ '/' | relative_url }}">Inicio</a>
      <a href="{{ '/investigacion/' | relative_url }}">Investigación</a>
      <a href="{{ '/publicaciones/' | relative_url }}">Publicaciones</a>
      <a href="{{ '/equipo/' | relative_url }}">Equipo</a>
      <a href="{{ '/proyectos/' | relative_url }}">Proyectos</a>
      <a href="{{ '/posts/' | relative_url }}">Blog</a>
      <a href="{{ '/contacto/' | relative_url }}">Contacto</a>
    </nav>
  </div>
</section>

<main class="lab-main">

  <section class="welcome-section">
    <h2>Bienvenidos</h2>
    <p>
      El <strong>Laboratorio de Neuroquímica de la UAEMex</strong> desarrolla investigación
      sobre procesos celulares y moleculares relacionados con cáncer de mama, glioblastoma,
      senescencia, apoptosis y agotamiento inmunológico.
    </p>
  </section>

  <section class="section-heading">
    <p>Explora nuestro sitio</p>
    <h2>Áreas principales</h2>
  </section>

  <section class="cards-lab">
    <a class="lab-card" href="{{ '/investigacion/' | relative_url }}">
      <span class="card-icon">🧠</span>
      <h3>Líneas de investigación</h3>
      <p>Conoce las áreas científicas que guían el trabajo del laboratorio.</p>
    </a>

    <a class="lab-card" href="{{ '/publicaciones/' | relative_url }}">
      <span class="card-icon">📚</span>
      <h3>Publicaciones</h3>
      <p>Consulta artículos, capítulos y producción académica del grupo.</p>
    </a>

    <a class="lab-card" href="{{ '/equipo/' | relative_url }}">
      <span class="card-icon">👩‍🔬</span>
      <h3>Equipo</h3>
      <p>Conoce a estudiantes, investigadores y colaboradores del laboratorio.</p>
    </a>

    <a class="lab-card" href="{{ '/proyectos/' | relative_url }}">
      <span class="card-icon">🧪</span>
      <h3>Proyectos en curso</h3>
      <p>Explora proyectos activos, colaboraciones y líneas con financiamiento.</p>
    </a>

    <a class="lab-card" href="{{ '/posts/' | relative_url }}">
      <span class="card-icon">📰</span>
      <h3>Blog y noticias</h3>
      <p>Actualizaciones, eventos, seminarios y novedades del laboratorio.</p>
    </a>

    <a class="lab-card" href="{{ '/contacto/' | relative_url }}">
      <span class="card-icon">📍</span>
      <h3>Contacto</h3>
      <p>Ubicación, correo y formas de comunicación con nuestro grupo.</p>
    </a>
  </section>

</main>