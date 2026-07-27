---
tipo_entidad: Universidad
financiacion:
  - "MOBULÆ Alliance"
  - "AuSpire"
ubicaciones:
  - "Launceston, Australia"
sitio_web: ""
portal_academico: ""
tags:
  - Universidad
---
## Perfil Institucional
Socia de [[Navantia]] (Monodon) a través de la MOBULÆ Alliance y el programa AuSpire.

## Grupos de Investigación, Laboratorios y Centros Mixtos
*(Centros singulares o laboratorios específicos adscritos o vinculados a esta universidad)*

| **Centro / Laboratorio** | **Línea de Investigación Principal** | **Nodos Tecnológicos** |
| ------------------------ | ------------------------------------- | ----------------------- |
| MOBULÆ Alliance / AuSpire | Robótica Submarina y Comunicaciones Ópticas | [[Monodon]] |

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
