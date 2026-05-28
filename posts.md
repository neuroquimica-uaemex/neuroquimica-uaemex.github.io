---
layout: null
title: Blog y protocolos
permalink: /posts/
---

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blog y protocolos | Laboratorio de Neuroquímica</title>
  <link rel="stylesheet" href="/assets/css/lab.css">
</head>

<body>
  <header class="page-header-lab">
    <nav class="main-nav-lab">
      <a href="/">Inicio</a>
      <a href="/investigacion/">Investigación</a>
      <a href="/publicaciones/">Publicaciones</a>
      <a href="/equipo/">Equipo</a>
      <a href="/proyectos/">Proyectos</a>
      <a href="/posts/">Blog</a>
      <a href="/contacto/">Contacto</a>
    </nav>
  </header>

  <main class="content-page">
    <section class="page-title">
      <p>Noticias, recursos y métodos</p>
      <h1>Blog y protocolos</h1>
    </section>

    <section class="content-card intro-card">
      <p>
        En esta sección compartiremos noticias del laboratorio, actualizaciones académicas
        y protocolos experimentales utilizados en nuestras líneas de investigación.
      </p>
    </section>

    <section class="blog-grid">
      <article class="blog-feature-card">
        <span class="card-icon">📰</span>
        <h2>Entradas del blog</h2>
        <p>
          Publicaciones sobre eventos, seminarios, avances del laboratorio,
          participación en congresos y novedades académicas.
        </p>
      </article>

      <article class="blog-feature-card">
        <span class="card-icon">🧪</span>
        <h2>Protocolos</h2>
        <p>
          Recursos metodológicos como Western blot, cristal violeta, cultivo celular,
          ensayos de viabilidad y otros procedimientos experimentales.
        </p>
      </article>
    </section>

    <section class="team-section">
      <h2>Publicaciones recientes</h2>

      <div class="content-card">
        {% if site.posts.size > 0 %}
          <ul class="post-list-lab">
            {% for post in site.posts %}
              <li>
                <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
                <p>{{ post.date | date: "%d/%m/%Y" }}</p>

                {% if post.excerpt %}
                  <div class="post-excerpt">
                    {{ post.excerpt }}
                  </div>
                {% endif %}
              </li>
            {% endfor %}
          </ul>
        {% else %}
          <p>
            Próximamente publicaremos noticias, actualizaciones y protocolos del laboratorio.
          </p>
        {% endif %}
      </div>
    </section>

    <section class="team-section">
      <h2>Protocolos destacados</h2>

      <div class="protocol-grid">
        <article class="protocol-card">
          <h3>Western blot</h3>
          <p>Protocolo para extracción, separación y detección de proteínas.</p>
          <span>Próximamente</span>
        </article>

        <article class="protocol-card">
          <h3>Cristal violeta</h3>
          <p>Ensayo para evaluación de viabilidad, proliferación o densidad celular.</p>
          <span>Próximamente</span>
        </article>

        <article class="protocol-card">
          <h3>Cultivo celular</h3>
          <p>Procedimientos generales para mantenimiento y tratamiento de líneas celulares.</p>
          <span>Próximamente</span>
        </article>
      </div>
    </section>
  </main>

  <footer class="footer-lab">
    <p>Laboratorio de Neuroquímica · Universidad Autónoma del Estado de México</p>
  </footer>
</body>
</html>