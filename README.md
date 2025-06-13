# RDF de Agentes - Proyecto de Identificadores Normalizados

Este repositorio contiene un conjunto de datos RDF/XML sobre agentes personales con sus respectivos identificadores normalizados, así como una versión HTML para visualización.

## Archivos incluidos

### 📄 `agentes_persona_P50094.rdf`
Archivo en formato RDF/XML compatible con el vocabulario del **RDA Registry**. Incluye:

- Descripción de agentes personales
- Identificadores normalizados agregados con la propiedad `rdaa:P50094`:
  - ISNI
  - ORCID
  - Wikidata
  - VIAF
  - LCNAF
  - Código UNAM

El RDF es válido conforme al estándar RDF 1.1 y fue verificado con el validador oficial de W3C.

### 🌐 `index_identificadores_unificados.html`
Versión legible para humanos del contenido RDF. Para cada agente muestra:

- Nombre preferido
- Variantes del nombre
- Ocupación y campo de actividad
- Lugar de nacimiento y fallecimiento
- 📌 **Identificadores** agrupados en una sola sección:
  - Cada valor aparece limpio (por ejemplo, `0000 0000 5415 9798`) y enlazado.

## Visualización

Puedes ver el archivo `index_identificadores_unificados.html` directamente en el navegador local o desde GitHub Pages si lo configuras como sitio web estático.

## Licencia

Este proyecto es de uso académico y puede adaptarse bajo una licencia abierta conforme al contexto del repositorio (sugerencia: CC-BY 4.0).

---
✍️ Elaborado para proyectos de normalización de datos de autoridad en bibliotecas digitales y Linked Data.
