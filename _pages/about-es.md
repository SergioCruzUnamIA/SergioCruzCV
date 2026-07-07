---
layout: about
title: Sergio Cruz
permalink: /es/
subtitle: Profesor en Ciencias de la Computación, Universidad Nacional Autónoma de México (UNAM)

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Oficina 130, Edificio de Matemáticas, UNAM</p>
    <p>Teléfono: 5556225429</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<!-- The shared navbar (al_folio_core, not owned by this starter) has no language
     awareness and always links to the English pages. This client-side patch
     retargets navbar links to their Spanish counterparts on /es/ pages. -->
<script>
  (function () {
    var path = window.location.pathname;
    var esIndex = path.indexOf("/es/");
    if (esIndex === -1) return;
    var base = path.slice(0, esIndex);
    var esPaths = {
      "/": "/es/",
      "/teaching/": "/es/docencia/",
      "/publications/": "/es/investigacion/",
      "/prospective-students/": "/es/oferta-de-trabajo/",
      "/office-hours/": "/es/horas-de-oficina/",
    };
    document.querySelectorAll("#navbar a[href]").forEach(function (link) {
      var href = link.getAttribute("href");
      var relative = href.indexOf(base) === 0 ? href.slice(base.length) : href;
      if (esPaths[relative]) {
        link.setAttribute("href", base + esPaths[relative]);
      }
    });
  })();
</script>

[🇬🇧 Read in English]({{ "/" | relative_url }})

Mi interés se centra en el Aprendizaje Profundo y Visión por Computadora/Detección de Objetos. Me interesa avanzar hacia temas más profundos como la Segmentación de Imágenes, el Reconocimiento de Actividades y la Inteligencia Artificial en general. Quiero aplicar el Aprendizaje Profundo a problemas de actividad diaria en la vida de las personas y mejorar su calidad de vida.

Ver también: [docencia]({{ "/es/docencia/" | relative_url }}), [investigación]({{ "/es/investigacion/" | relative_url }}), [horas de oficina]({{ "/es/horas-de-oficina/" | relative_url }}), y [oferta de trabajo]({{ "/es/oferta-de-trabajo/" | relative_url }}) para estudiantes.

#### Experiencia Laboral

**Hong Kong Applied Science and Technology Research Institute (ASTRI)** — Ingeniero Senior, Junio 2021 – Noviembre 2023

Con más de 2 años de experiencia como Ingeniero Senior en ASTRI, mejoré la precisión de reconocimiento de caracteres mediante la implementación de un modelo de Aprendizaje Profundo para OCR en inglés y chino, lo que resultó en una mayor eficiencia y satisfacción del cliente.

- Detección de caracteres impresos con PyTorch y YOLO. Aumenté la precisión de detección de caracteres en un 15% mediante esta implementación.
- Segmentación de caracteres impresos con PyTorch y YOLO. Reduje el tiempo de segmentación de imágenes en un 20%. Mejoré el control de calidad y reduje el tiempo de entrenamiento.
- Diseñé y presenté una patente para generar datos personalizados combinando tecnologías de IA Generativa y Procesamiento del Lenguaje Natural (NLP).

#### Educación

**City University of Hong Kong**, Hong Kong — Sep 2014 – Mar 2021
Doctorado en Ciencias de la Computación
Tesis: _Hand Disambiguation in the Egocentric Perspective_

**Benemérita Universidad Autónoma de Puebla** — Sep 2012 – Aug 2014
Maestría en Ciencias de la Computación
Tesis: _Gait Analysis of the Inferior Articulations of Healthy People and with Locomotion Problems_

**Benemérita Universidad Autónoma de Puebla** — Sep 2006 – Aug 2012
Ingeniería en Ciencias de la Computación
Programa de Intercambio en Bishop's University, Sherbrooke, Canadá (2010–2011)

Para cualquier pregunta o contacto, use la siguiente información:
Teléfono: 5556225429
Oficina: 130, Edificio de Matemáticas, UNAM
