---
layout: page
permalink: /es/docencia/
title: docencia
description: Cursos impartidos en la Universidad Nacional Autónoma de México (UNAM), Facultad de Ciencias.
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

[🇬🇧 Read in English]({{ "/teaching/" | relative_url }})

Estoy dando tres cursos este semestre en la Universidad Nacional Autónoma de México (UNAM). Por favor, inscribirse a los cursos por medio de la página de la universidad. Si tienes dudas específicas acerca de los temas dados en los cursos, por favor mandame un correo, y te responderé a la brevedad posible.

## 7000: Inteligencia Artificial

Semestre: Otoño · Año: 2025 · Código: 2026-1

Conocerá conceptos clave y aplicaciones de la inteligencia artificial. Adquirirá una experiencia extensa con algún lenguaje que se utilice comúnmente para sistemas de IA.

[Temario](https://www.fciencias.unam.mx/sites/default/files/temario/608.pdf)

## 7149: Reconocimiento de Patrones y Aprendizaje Automatizado

Semestre: Otoño · Año: 2025 · Código: 2026-1

Conocer y aplicar una visión general de las diferentes técnicas utilizadas para clasificar objetos representados en la computadora, extraer y seleccionar sus características. Comprender los fundamentos de las técnicas supervisadas y no supervisadas para el reconocimiento de patrones y para el aprendizaje automático. Poseer los elementos necesarios para comprender y elaborar aplicaciones simples del reconocimiento de patrones y aprendizaje automático.

[Temario](https://www.fciencias.unam.mx/sites/default/files/temario/773.pdf)

## 7043: Introducción a Ciencias de la Computación

Semestre: Otoño · Año: 2025 · Código: 2026-1

Brindar al estudiante los conocimientos fundamentales de la computación y de la programación orientada a objetos, desarrollando habilidades para diseñar, codificar y depurar aplicaciones mediante el uso adecuado de estructuras de datos, principios de diseño orientado a objetos, herencia, manejo de errores, persistencia de datos y ejecución concurrente, a fin de formar una base sólida para cursos avanzados en desarrollo de software.

[Temario](https://web.fciencias.unam.mx/asignaturas/1125.pdf)

## Semestres anteriores

- **7001, 7002: Inteligencia Artificial** — Primavera 2025, Código: 2025-2 — [Temario](https://www.fciencias.unam.mx/sites/default/files/temario/608.pdf)
- **7152: Reconocimiento de Patrones y Aprendizaje Automatizado** — Primavera 2025, Código: 2025-2 — [Temario](https://www.fciencias.unam.mx/sites/default/files/temario/773.pdf)
- **7000, 7172: Inteligencia Artificial** — Otoño 2024, Código: 2025-1 — [Temario](https://www.fciencias.unam.mx/sites/default/files/temario/608.pdf)
- **7120: Reconocimiento de Patrones y Aprendizaje Automatizado** — Otoño 2024, Código: 2025-1 — [Temario](https://www.fciencias.unam.mx/sites/default/files/temario/773.pdf)
