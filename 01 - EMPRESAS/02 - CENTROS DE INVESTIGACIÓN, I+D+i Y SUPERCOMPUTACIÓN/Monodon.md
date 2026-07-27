---
tipo_entidad: Centro de investigación
sectores: Defensa, Robótica Submarina y Tecnologías Deep-Tech
matriz: "[[Navantia]]"
tipo_relacion: ""
ubicaciones:
  - Cádiz (Cádiz)
Dirección:
location:
sitio_web: https://monodon.com
Linkedin: https://www.linkedin.com/company/monodon_navantia/
telefono:
email:
tags:
  - Empresa
---
## Perfil de la entidad
*(Breve descripción de las líneas de actividad, mercado objetivo y relevancia estratégica de la organización)*

Monodon es el departamento de investigación y desarrollo de base tecnológica (deep-tech) de [[Navantia]]. Su objetivo principal es crear productos y soluciones de doble uso (civil y militar) fundamentados en la ciencia básica, aprovechando e integrándose activamente en el ecosistema de investigación internacional. A través de un enfoque de innovación abierta, Monodon colabora estrechamente con expertos del ámbito académico, startups y corporaciones industriales para resolver desafíos complejos de ingeniería en entornos de operación críticos.

La visión tecnológica de Monodon se vertebra en cuatro grandes pilares estratégicos: sistemas autónomos, nanotecnología, comunicaciones ópticas y tecnologías cuánticas. Su labor abarca desde la modernización de los sistemas de navegación submarina independientes de satélites (GNSS), hasta la creación de redes de comunicación láser de banda ancha bajo el agua y el diseño de nuevos materiales bioinspirados. Adicionalmente, el departamento actúa como fuerza tractora en el sector de las energías renovables offshore (eólica marina), perfilando el futuro de las infraestructuras de defensa y energía a través de cátedras conjuntas y consorcios universitarios.

## Tecnologías y líneas de investigación / Áreas de trabajo
*(Lista de líneas de investigación y trabajo de la empresa con su descripción y con las empresas con las que colaboran en ese aspecto)*


| **Línea de trabajo**                           | **Descripción (Incluye aquí los enlaces a los Nodos Tecnológicos en INGLÉS)**                                                                                                                                                                                                                                                                                                                                   | **Otras empresas asociadas**                                                                                                                                                    |
| ---------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sistemas Autónomos y Robótica Submarina        | Diseño y despliegue de plataformas robóticas multi-dominio (Vehículos de Superficie No Tripulados y AUVs) apoyadas en [[Autonomous Systems]]. Incorporación de técnicas de sensórica avanzada mediante [[Neuromorphic and Vision Sensors]] y computación bioinspirada para operaciones de exploración marina.                                                                                                   | [[Australian Maritime College (AMC)]]                                                                                                                                           |
| Tecnologías Cuánticas de Navegación (Q-NAVIUM) | Desarrollo del proyecto Q-NAVIUM enfocado en la validación de magnetómetros y giroscopios basados en [[Quantum Sensors]] para aplicaciones navales. Utiliza diamantes con [[Nitrogen-Vacancy Center]] para garantizar navegación inercial ininterrumpida en entornos submarinos donde la señal GPS/GNSS no está disponible. Exploración de arquitecturas de [[Reservoir Computing]] en materiales spintrónicos. |                                                                                                                                                                                 |
| Nanotecnología y Materiales Avanzados          | Investigación en metamateriales mecánicos reprogramables, estructuras magneto-activas ultra-blandas e impresión de polímeros. Desarrollo de recubrimientos biodegradables marinos ("antifouling") mediante [[Nanotechnology]] y diseño de actuadores para aplicaciones en robótica blanda ("Soft Robotics").                                                                                                    | [[Universidad Carlos III de Madrid (UC3M)]], [[University of Michigan]], [[Universidad Politécnica de Cartagena (UPCT)]], [[Institut Polytechnique de Paris]], [[Biomimetic]]   |
| Comunicaciones Ópticas y Fotónica              | Creación de enlaces de comunicaciones mediante láser y arquitecturas de [[Photonic and Optical Technologies]] para entornos espaciales y submarinos de alta demanda de ancho de banda. Incorporación de sistemas integrados y desarrollo experimental evaluado en programas como el ecosistema PULSE y la iniciativa AuSpire.                                                                                   | [[Universidad de Vigo (UVIGO)]], [[QOPHI Photonics]] (Laboratorio de investigación fotónica y comunicaciones), [[RMIT University]], [[Universidad Politécnica de Madrid (UPM)]] |

## Sedes y centros de trabajo
*(Oficinas, laboratorios, observatorios, talleres...)*

| **LOCALIDAD (Provincia)** | **Tipo de sede**                                                                              | **Dirección**  |
| ------------------------- | --------------------------------------------------------------------------------------------- | -------------- |
| [[Cádiz (Cádiz)]]         | Entorno de experimentación naval (Bahía de Cádiz para validación de USVs y nuevos materiales) | Bahía de Cádiz |

## Contactos dentro de la empresa
*(Tabla rápida de referencia; la ficha completa de cada persona vive en 04 - CONTACTOS)*

| **Nombre y Apellidos** | **Puesto** | **Email** | **Teléfono** | **Enlace Linkedin** |
| ----------------------- | ---------- | --------- | ------------ | -------------------- |
| Arnan Mitchell | Co-Supervisor de Investigación postdoctoral (RMIT University) | | | |
| Abdon Pena-Francesch | Investigador Colaborador y Profesor (University of Michigan) | | | |
| Daniel García González | Investigador Colaborador (Materiales magnéticos blandos) | | | |
| Concepción Monje | Investigadora Colaboradora (Robótica blanda) | | | |
| Rafael García | Investigador Colaborador (Sensores neuromórficos y bioinspirados) | | | |

## Fuentes consultadas

- monodon (https://monodon.com/)
- Autonomous Systems – monodon (https://monodon.com/technology/autonomous-systems/)
- Nanotechnology – monodon (https://monodon.com/technology/nanotechnology/)
- Optical Communications – monodon (https://monodon.com/technology/opcomms/)
- Quantum – monodon (https://monodon.com/technology/quantum/)
- [[QOPHI Photonics]] (https://qophi.eu/)

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
