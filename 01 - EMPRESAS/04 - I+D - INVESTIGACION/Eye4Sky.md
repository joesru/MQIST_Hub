---
aliases:
  - Eye4Sky
  - Eye4Sky Technologies
  - Eye4Sky Technologies S.L.
tipo_entidad: Startup
sectores: Aeroespacial-Defensa
matriz: "[[Instituto Nacional de Técnica Aeroespacial (INTA)]]"
tipo_relacion: Spin-off
ubicaciones:
  - "[[Madrid (Madrid)]]"
Dirección:
  - Parque Científico de Madrid, c/ Faraday 7, 28049 Madrid
location: 40.54909746327217, -3.6891595792466734
sitio_web: https://www.eye4sky.com/
Linkedin: https://www.linkedin.com/company/eye4sky/
telefono:
email: info@eye4sky.com
tags:
  - Empresa
---
## Perfil de la entidad
*(Breve descripción de las líneas de actividad, mercado objetivo y relevancia estratégica de la organización)*

Eye4Sky Technologies es una startup *deep-tech* y la primera spin-off surgida del [[Instituto Nacional de Técnica Aeroespacial (INTA)]]. Su actividad principal consiste en el desarrollo y comercialización de tecnología óptica avanzada para el espacio, centrándose específicamente en moduladores de polarización basados en retardadores variables de cristal líquido (LCVR). Esta tecnología, que ha alcanzado el máximo grado de madurez (TRL9), permite controlar, modificar y medir el estado de polarización de la luz minimizando drásticamente la masa, el volumen y el consumo de potencia de las cargas útiles, lo que la hace idónea para constelaciones de pequeños satélites en el ecosistema New Space.

A nivel estratégico, la tecnología de Eye4Sky ha sido cualificada y validada en misiones de primer nivel internacional. Sus dispositivos operan actualmente en la sonda Solar Orbiter (instrumentos SO/PHI y METIS) liderada por la Agencia Espacial Europea en colaboración con la NASA. Además, se han integrado en proyectos como Sunrise III, NanoMagSat y la futura misión Vigil. La empresa expande sus campos de aplicación más allá de la observación de la Tierra y la astrofísica hacia áreas críticas y disruptivas como los relojes atómicos y las comunicaciones cuánticas satelitales, habiendo sido respaldada financieramente por programas de prestigio como NEOTEC, ESA BIC y el clúster Madrid Innovation New Space Cluster (MINSC).

## Tecnologías y líneas de investigación / Áreas de trabajo
*(Lista de líneas de investigación y trabajo de la empresa con su descripción y con las empresas con las que colaboran en ese aspecto)*


| **Línea de trabajo** | **Descripción (Incluye aquí los enlaces a los Nodos Tecnológicos en INGLÉS)** | **Otras empresas asociadas** |
| --------------------- | ---------------- | ----------------------------- |
| Moduladores de Polarización Espacial (LCVR) | Desarrollo de retardadores variables de cristal líquido y analizadores de polarización de Stokes (lineales y completos) para misiones espaciales e instrumentación astrofísica empleando [[Photonic and Optical Technologies]]. | [[Instituto Nacional de Técnica Aeroespacial (INTA)]], [[Agencia Espacial Europea (ESA)]], [[NASA]] |
| Comunicaciones Cuánticas por Satélite (LEO-QKD) | Diseño del primer sistema español de distribución de claves cuánticas espaciales. Desarrollo de sistemas de seguimiento de polarización para protocolos de preparación y medida como el [[BB84 Protocol]] y el [[B92 Protocol]], así como protocolos de entrelazamiento como el [[Ekert 91 Protocol]] en redes de [[Quantum Key Distribution]]. | [[Centro para el Desarrollo Tecnológico y la Innovación (CDTI)]] |
| Relojes Atómicos y Atrapamiento de Población | Desarrollo de moduladores de polarización orientados al atrapamiento coherente de población (CPT) de alto rendimiento y técnicas de Doble Modulación (DM-CPT) para la próxima generación de [[Quantum Sensors]] y relojes atómicos espaciales. | |

## Sedes y centros de trabajo
*(Oficinas, laboratorios, observatorios, talleres...)*


| **LOCALIDAD (Provincia)** | **Tipo de sede** | **Dirección** |
| -------------------------- | ----------------- | -------------- |
| [[Madrid (Madrid)]] | Sede central y oficinas corporativas | Parque Científico de Madrid, c/ Faraday 7, 28049 Madrid |

## Contactos dentro de la empresa
*(Tabla rápida de referencia; la ficha completa de cada persona vive en 04 - CONTACTOS)*

| **Nombre y Apellidos** | **Puesto** | **Email** | **Teléfono** | **Enlace Linkedin** |
| ----------------------- | ---------- | --------- | ------------ | -------------------- |
| Alberto Álvarez Herrero | Chief Scientific Officer (CSO) | | | |
| Pilar García Parejo | Chief Technical Officer (CTO) | | | |
| Delia Rodríguez de Llera González | Chief Executive Officer (CEO) | | | |
| Manuel Faraco Favieres | Advisor to the Board | | | |

## Fuentes consultadas

- https://www.eye4sky.com/
- https://www.eye4sky.com/eye4sky/
- https://www.eye4sky.com/what-we-offer/
- https://www.eye4sky.com/why-we-are-different/
- https://www.eye4sky.com/application-fields/
- https://www.eye4sky.com/news/

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
