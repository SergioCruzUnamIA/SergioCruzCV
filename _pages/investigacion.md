---
layout: page
permalink: /es/investigacion/
title: investigación
description: Publicaciones organizadas por tipo y año.
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

[🇬🇧 Read in English]({{ "/publications/" | relative_url }})

Mas adelante, encontrarás mis trabajos organizados por tipo de publicación y año. Si tienes dudas específicas acerca de alguna publicación, por favor mandame un correo, y te responderé a la brevedad posible.

Consulta la lista completa en la [página de publicaciones]({{ "/publications/" | relative_url }}) (los títulos de los artículos se mantienen en su idioma original de publicación).
