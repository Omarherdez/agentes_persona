# Proyecto de Autoridades Personales en RDF (RDA + Linked Data)

Este repositorio contiene un conjunto de datos estructurado en RDF/XML que describe agentes personales conforme al vocabulario del **RDA Registry**, incorporando identificadores normalizados en formato Linked Data.

---

## 📄 Archivos incluidos

### [`index.html`](./index.html)
Visualización legible en HTML con los siguientes elementos por agente:

- Nombre autorizado
- Variantes del nombre
- Ocupación y campo de actividad
- Lugar de nacimiento y fallecimiento
- **Fuentes consultadas**
- **Identificadores normalizados**, agrupados (ISNI, ORCID, VIAF, Wikidata, LCNAF, UNAM)

🔗 Puedes ver esta página en línea desde:  
[https://omarherdez.github.io/agentes_persona/](https://omarherdez.github.io/agentes_persona/)

---

### [`agentes_persona.rdf`](./agentes_persona.rdf)
Archivo en formato RDF/XML conforme al RDA Registry, incluye:

- Identificadores en formato Linked Data con `rdf:resource`
- Estructura validada con el [validador RDF del W3C](https://www.w3.org/RDF/Validator/)

---

## 🌐 Visualización en GitHub Pages

Este repositorio está configurado para visualizarse como un sitio web estático.  
Puedes acceder directamente aquí:  
🔗 **https://omarherdez.github.io/agentes_persona/**

---

## 📘 Licencia

Sugerimos el uso de la licencia:  
**Creative Commons Atribución 4.0 Internacional (CC BY 4.0)**  
(Salvo que la institución determine lo contrario)

---

## ✍️ Créditos

Elaborado como parte de un ejercicio de autoridad normalizada utilizando principios de **RDA**, **RDF/XML** y **Linked Data**, orientado a su aplicación en bibliotecas académicas, catálogos abiertos y repositorios institucionales.
