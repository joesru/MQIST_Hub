---
tipo_entidad: Universidad
financiacion:
ubicaciones:
sitio_web: ""
portal_academico: ""
tags:
  - Universidad
---
## Perfil Institucional
*(Breve resumen sobre la relevancia académica de la institución, facultades científico-técnicas principales e impacto en el ecosistema de I+D+i).*


## Grupos de Investigación, Laboratorios y Centros Mixtos
*(Espacio para listar los centros singulares o laboratorios específicos adscritos o vinculados a esta universidad. Ej: VQCC, IMSE, SCBI).*

| **Centro / Laboratorio** | **Línea de Investigación Principal** | **Nodos Tecnológicos** |
| ------------------------ | ------------------------------------- | ----------------------- |
|                          |                                       |                         |

## Programas de Posgrado y Oferta Académica de Vanguardia
*(Listado de másteres universitarios, programas de doctorado o itinerarios de especialización de alto interés estratégico).*

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
