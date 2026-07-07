---
layout: page
permalink: /es/oferta-de-trabajo/
title: oferta de trabajo
description: Oportunidades de colaboración para estudiantes y futuros investigadores.
nav: false
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

[🇬🇧 Read in English]({{ "/prospective-students/" | relative_url }})

Ofrezco las siguientes oportunidades de colaboración para estudiantes y futuros investigadores:

#### Oportunidades para Estudiantes de Licenciatura

**Ayudantes de Curso y/o de Laboratorio**

Estoy buscando estudiantes de Licenciatura que deseen participar como ayudantes en los cursos que impartiré este semestre. Podrás colaborar tanto en la docencia como en las actividades de laboratorio, adquiriendo valiosa experiencia práctica y académica.

**Tesis de Licenciatura**

Si eres estudiante de Licenciatura y estás buscando un tema para tu tesis, tengo proyectos innovadores que te puedo sugerir en áreas como Segmentación de Imágenes, Reconocimiento de Actividades y Detección de Objetos. También estoy abierto a discutir temas que ya tengas en mente.

**Servicio Social**

Si necesitas realizar tu Servicio Social, ofrezco proyectos en los que podrás colaborar en actividades de investigación y desarrollo tecnológico. Tendrás la oportunidad de contribuir a proyectos en curso mientras fortaleces tus habilidades técnicas y analíticas en áreas relacionadas con visión por computadora, inteligencia artificial y ciencia de datos.

#### Requisitos

Para Licenciatura: interés en investigación y colaboración en áreas tecnológicas, con conocimientos básicos de programación.

#### Cómo Postular

Si estás interesado/a en cualquiera de estas oportunidades, envíame un correo electrónico con tu CV y una breve descripción de tu propuesta o intereses de investigación.

#### Trabajos

- **Ayudante de Curso**: Se enfoca en la definición de problemas/ejercicios para ser explicados/presentados presencialmente y para calificar el curso.
- **Ayudante de Laboratorio**: Se enfoca en la definición de programas para ser explicados/presentados presencialmente y para calificar el curso.
- **Estudiante de Tésis**: Se enfoca en hacer investigación con objetivos en publicaciones y tésis de Licenciatura.
