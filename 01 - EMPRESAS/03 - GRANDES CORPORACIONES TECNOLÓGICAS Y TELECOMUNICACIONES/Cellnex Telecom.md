---
aliases:
  - Cellnex
tipo_entidad: Empresa Privada
sectores: Infraestructuras de Telecomunicaciones y Radiodifusión
matriz: Independiente
tipo_relacion: ""
ubicaciones:
  - Madrid (Madrid)
  - Barcelona (Barcelona)
Dirección:
location:
sitio_web: https://www.cellnex.com
Linkedin: https://www.linkedin.com/company/cellnextelecom
telefono:
email:
tags:
  - Empresa
---
## Perfil de la entidad
*(Breve descripción de las líneas de actividad, mercado objetivo y relevancia estratégica de la organización)*

Cellnex Telecom es una multinacional española y el principal operador independiente de infraestructuras de telecomunicaciones inalámbricas y de radiodifusión en Europa. Con una capitalización bursátil que la sitúa en los selectivos IBEX 35 y Euro Stoxx 600, la compañía gestiona más de 114.000 emplazamientos operativos distribuidos en una decena de países europeos. Su modelo de negocio se estructura en áreas clave que incluyen el alquiler de emplazamientos para operadores de telefonía móvil, el despliegue de redes de fibra óptica, el alojamiento en centros de datos y la implementación de sistemas de antenas distribuidas (DAS) y celdas pequeñas (Small Cells) para garantizar la conectividad de banda ancha en entornos de muy alta densidad.

En el paradigma de las comunicaciones seguras y la ciberseguridad, Cellnex asume un rol proactivo en el despliegue de infraestructuras terrestres para el futuro Internet Cuántico. Como miembro del consorcio internacional [[Quantum Internet Alliance]] (QIA), la compañía colabora en el diseño de las plataformas europeas de información cuántica. A nivel nacional, Cellnex participa en consorcios estratégicos y proyectos financiados con fondos europeos como Q-NETWORKS, coordinando el testeo y la validación de tecnologías de encriptación cuántica sobre la infraestructura comercial de fibra óptica para neutralizar las amenazas derivadas de los futuros ordenadores cuánticos.

Adicionalmente a su implicación en la vanguardia cuántica, Cellnex actúa como una fuerza tractora en la transformación digital europea mediante el desarrollo de ecosistemas para el Internet de las Cosas (IoT), el despliegue de soluciones 5G y redes privadas, y la provisión de comunicaciones de misión crítica. Sus infraestructuras son críticas para los cuerpos de seguridad, el salvamento marítimo, el ecosistema agrícola y el transporte conectado, integrando tecnologías de procesamiento en el borde (Edge Computing) y de virtualización adaptativa mediante inteligencia artificial para garantizar servicios de muy baja latencia.

## Tecnologías y líneas de investigación / Áreas de trabajo
*(Lista de líneas de investigación y trabajo de la empresa con su descripción y con las empresas con las que colaboran en ese aspecto)*


| **Línea de trabajo** | **Descripción (Incluye aquí los enlaces a los Nodos Tecnológicos en INGLÉS)** | **Otras empresas asociadas** |
| --------------------- | ---------------- | ----------------------------- |
| Redes Cuánticas Terrestres y Ciberseguridad | Participación en la infraestructura del [[Quantum Internet]] europeo a través de la [[[[Quantum Internet Alliance]]|[[[[Quantum Internet Alliance]]|QIA]]]]. Coordinación del proyecto Q-NETWORKS para el despliegue de enlaces de [[Quantum Key Distribution]] sobre las redes de fibra óptica comerciales, garantizando el transporte seguro de datos frente a ataques cuánticos. | [[Instituto de Ciencias Fotónicas (ICFO)]], [[Xarxa Oberta de Catalunya (XOC)]], [[Telefónica]], [[Universidad Politécnica de Madrid (UPM)]], [[Thales Alenia Space]], [[Quantum Internet Alliance (QIA)]] |
| Conectividad 5G, DAS y Small Cells | Implementación de arquitecturas de [[5G]] y conectividad ininterrumpida mediante Distributed Antenna Systems (DAS) en estadios, aeropuertos y transportes. Provisión de [[Broadband Networks]] neutrales para múltiples operadores de telecomunicaciones a nivel internacional. | [[MasOrange]], [[Bouygues Telecom]], [[Iliad]], [[NOS]], [[CK Hutchison]], [[SFR]], [[Telefónica]], [[Aena]], [[RC Celta de Vigo]], [[Ferrocarrils de la Generalitat de Catalunya (FGC)]] |
| Comunicaciones de Misión Crítica e IoT | Diseño de redes inquebrantables y ecosistemas para el [[Internet of Things]]. Provisión de comunicaciones seguras de voz y datos (TETRA/LTE) orientadas a servicios de seguridad, emergencias, salvamento marítimo y telemetría de infraestructuras críticas. | [[Airbus]], [[Securitas Direct]], [[Salvamento Marítimo]], [[Gobierno de las Islas Baleares (IBETEC)]], [[ENAIRE]] |
| Edge Computing y Virtualización Adaptativa | Despliegue de nodos de procesamiento de datos distribuidos bajo paradigmas de [[Edge Computing]] (Proyecto CloudSkin). Empleo de [[Artificial Intelligence and Machine Learning]] para gestionar recursos cloud-edge garantizando continuidad operativa con ultra baja latencia. | [[Unión Europea (NextGenerationEU)]] |

## Sedes y centros de trabajo
*(Oficinas, laboratorios, observatorios, talleres...)*

| **LOCALIDAD (Provincia)** | **Tipo de sede**                       | **Dirección**                        |
| ------------------------- | -------------------------------------- | ------------------------------------ |
| [[Madrid (Madrid)]]       | Sede Social (Trasladada en 2017)       | Calle Juan Esplandiú, Madrid, España |
| [[Barcelona (Barcelona)]] | Sede Operativa y corporativa principal | Barcelona, España                    |
# Contactos dentro de la empresa
*(Tabla rápida de referencia; la ficha completa de cada persona vive en 04 - CONTACTOS)*

| **Nombre y Apellidos** | **Puesto** | **Email** | **Teléfono** | **Enlace Linkedin** |
| ----------------------- | ---------- | --------- | ------------ | -------------------- |
|                         |            |           |              |                      |
|                         |            |           |              |                      |
|                         |            |           |              |                      |

## Fuentes consultadas



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
