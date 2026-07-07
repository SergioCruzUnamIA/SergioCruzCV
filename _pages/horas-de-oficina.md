---
layout: page
permalink: /es/horas-de-oficina/
title: horas de oficina
description: Horas de oficina en la Universidad Nacional Autónoma de México (UNAM).
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

[🇬🇧 Read in English]({{ "/office-hours/" | relative_url }})

Las horas de oficina son de Lunes a Miércoles, 11am–3pm.

Oficina: Cubículo 130, Edificio de Matemáticas, UNAM.
