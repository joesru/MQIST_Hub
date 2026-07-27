---
tipo_entidad: Universidad
financiacion:
  - "Centro de Supercomputación de Galicia (CESGA)"
  - "Fujitsu – International Quantum Center"
ubicaciones:
  - "A Coruña, España"
sitio_web: ""
portal_academico: ""
tags:
  - Universidad
---
## Perfil Institucional
La Universidade da Coruña colabora estrechamente con el CESGA y con Fujitsu en el desarrollo del International Quantum Center, y alberga el centro singular CITIC, especializado en inteligencia artificial y algoritmia cuántica.

## Grupos de Investigación, Laboratorios y Centros Mixtos
*(Centros singulares o laboratorios específicos adscritos o vinculados a esta universidad)*

| **Centro / Laboratorio** | **Línea de Investigación Principal** | **Nodos Tecnológicos** |
| ------------------------ | ------------------------------------- | ----------------------- |
| CITIC | Inteligencia Artificial y Algoritmia Cuántica | [[Centro de Supercomputación de Galicia (CESGA)]], [[Fujitsu]] |

## Programas de Posgrado y Oferta Académica de Vanguardia
*(Listado de másteres universitarios, programas de doctorado o itinerarios de especialización de alto interés estratégico)*

- 

## 🏢 Centros e Institutos Dependientes (Vía Dataview)
*(Muestra automáticamente los laboratorios o centros cuya matriz es esta universidad)*

```dataview
TABLE
    sector AS "Especialización",
    ubicaciones AS "Sede"
FROM "01 - EMPRESAS"
WHERE matriz = this.file.link OR contains(matriz, this.file.link)
SORT file.name ASC
```
