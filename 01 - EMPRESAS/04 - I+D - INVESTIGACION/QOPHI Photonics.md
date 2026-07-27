---
tipo_entidad: Centro de Investigación
sectores: Fotónica, Comunicaciones Ópticas y Cuánticas
matriz: "[[Universidad de Vigo (UVIGO)]]"
tipo_relacion: ""
ubicaciones:
  - Vigo (Pontevedra)
Dirección:
  - "Campus de Vigo As Lagoas, Rúa Maxwell, s/n, 36310 Vigo, Pontevedra (Laboratorio: B010)"
location:
sitio_web: https://qophi.eu
Linkedin:
telefono:
email:
tags:
  - Empresa
---
## Perfil de la entidad
*(Breve descripción de las líneas de actividad, mercado objetivo y relevancia estratégica de la organización)*

QOPHI Photonics (QOPHI Lab) es un avanzado laboratorio de investigación adscrito a la [[Universidad de Vigo (UVIGO)|Universidad de Vigo]], centrado en la generación de conocimiento científico de alta calidad en el ámbito de las comunicaciones clásicas y cuánticas, la fotónica y la fotónica integrada. El centro opera una infraestructura de vanguardia diseñada para la caracterización y prueba experimental de componentes ópticos pasivos y activos, circuitos integrados y dispositivos electroópticos. Su enfoque abarca la totalidad de la cadena de valor, desde el análisis teórico y el diseño hasta la validación empírica en laboratorio.

El laboratorio actúa como un nodo de transferencia tecnológica esencial, colaborando estrechamente con el sector privado a través de contratos de I+D y cátedras conjuntas, tales como la Cátedra [[Navantia]] [[Monodon]] y la Cátedra NextChip. Su actividad investigadora abarca un abanico diverso que va desde el diseño de redes de comunicaciones ópticas subacuáticas para robótica hasta la validación de configuraciones discretas y ultra silenciosas para la distribución de claves cuánticas comerciales.

A nivel europeo, QOPHI desempeña un papel de liderazgo coordinando y participando en múltiples consorcios de las Acciones Marie Skłodowska-Curie (MSCA DN), destacando proyectos como [[MWP4SPACE]], RETINA, DRIVE-In y EDIFY. A través de estas iniciativas, el laboratorio impulsa la superación de barreras técnicas en la fabricación industrial de circuitos fotónicos y el desarrollo de pozos cuánticos avanzados, uniendo la investigación académica profunda con la capacidad de fabricación a escala de las principales fundiciones europeas.

## Tecnologías y líneas de investigación / Áreas de trabajo
*(Lista de líneas de investigación y trabajo de la empresa con su descripción y con las empresas con las que colaboran en ese aspecto)*


| **Línea de trabajo** | **Descripción (Incluye aquí los enlaces a los Nodos Tecnológicos en INGLÉS)** | **Otras empresas asociadas** |
| --------------------- | ---------------- | ----------------------------- |
| Fabricación e Integración de Circuitos Fotónicos (Proyectos EDIFY y DRIVE-In) | Diseño, desarrollo y modelado compacto de [[Photonic Integrated Circuit]] basados en tecnología de fosfuro de indio (InP). Generación de pozos cuánticos con aluminio para dispositivos activos y evaluación de rendimiento para su futura automatización en fundiciones fotónicas. Orientado a aplicaciones en telecomunicaciones, datacom y sistemas vehiculares. | [[Technische Universiteit Eindhoven (TU/e)]], [[SMART Photonics BV]], [[Bright Photonics BV]], [[Photon Design]], [[Phoenix BV]], [[Fraunhofer Institute for Telecommunications (HHI)]], [[VPI Photonics]] |
| Comunicaciones Cuánticas y Criptografía | Implementación de configuraciones experimentales y caracterización de enlaces ópticos de [[Quantum Key Distribution]] apoyados por sistemas de medición de ruido ultra bajo. Verificación de atenuación, dispersión cromática y prueba de robustez en redes ópticas para garantizar la transmisión segura de fotones. | [[Universidad de Vigo (UVIGO)]] |
| Comunicaciones Ópticas y Sensórica | Desarrollo y caracterización de transceptores, láseres sintonizables de ancho de línea estrecho y tecnologías de [[Sensing and Measurement Technologies]]. Investigación en [[Optical Communications]] aplicadas a la robótica subacuática, radares y sensores de profundidad en colaboración con ecosistemas de defensa y ecosistemas autónomos. | [[Navantia]] |

## Sedes y centros de trabajo
*(Oficinas, laboratorios, observatorios, talleres...)*

| **LOCALIDAD (Provincia)** | **Tipo de sede**                                   | **Dirección**                                                                          |
| ------------------------- | -------------------------------------------------- | -------------------------------------------------------------------------------------- |
| [[Vigo (Pontevedra)]]     | Laboratorio principal de investigación (QOPHI Lab) | Campus de Vigo As Lagoas, Rúa Maxwell, s/n, 36310 Vigo, Pontevedra (Laboratorio: B010) |

## Contactos dentro de la empresa
*(Tabla rápida de referencia; la ficha completa de cada persona vive en 04 - CONTACTOS)*

| **Nombre y Apellidos** | **Puesto** | **Email** | **Teléfono** | **Enlace Linkedin** |
| ----------------------- | ---------- | --------- | ------------ | -------------------- |
| Francisco Javier Díaz Otero | Investigador Principal | fjdiaz@com.uvigo.es | | |
| Francisco Soares | Miembro del Comité de Dirección (Managing Committee) | | | |
| Vahram Voskerchyan | Investigador Postdoctoral | | | |
| Zahra Ahmadpanah | Investigadora Predoctoral (PhD) | | | |
| Lucía Amaro | Investigadora Predoctoral (PhD) | | | |
| Desirée González Fernández | Investigadora Junior | | | |
## Fuentes consultadas

- QOPHI Photonics. (2026). Research Areas. URL: https://qophi.eu/research-areas/
- QOPHI Photonics. (2026). EDIFY: European Doctorate in Indium Phosphide PIC Fabrication Techonology. URL: https://qophi.eu/projects/edify/
- QOPHI Photonics. (2026). DRIVE-In: Integrated Photonics for the next generation of autonomous Vehicles using InP technologies. URL: https://qophi.eu/projects/drive-in/
- [[Monodon]]. (2026). Optical Communications. URL: https://monodon.com/technology/opcomms/

---
## Histórico de ofertas y estado de candidaturas

```dataview
TABLE
    puesto AS "Puesto",
    ubicacion AS "Localización",
    fecha_publicacion AS "Publicada",
    cv_enviado AS "CV Enviado",
    fase AS "Fase",
    resultado AS "Resultado"
FROM "02 - OFERTAS"
WHERE contains(empresa, this.file.link)
SORT fecha_publicacion DESC
```

## Contactos vinculados (vía Dataview)
*(Se rellena solo a partir de las notas en 04 - CONTACTOS que apunten a esta empresa)*

```dataview
TABLE
    cargo AS "Cargo",
    email AS "Email",
    telefono AS "Teléfono",
    linkedin AS "LinkedIn"
FROM "04 - CONTACTOS"
WHERE contains(empresa, this.file.link)
SORT file.name ASC
```
