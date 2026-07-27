---
tipo_entidad: Universidad
financiacion:
  - "Red Española de Supercomputación (RES)"
ubicaciones:
  - "[[Zaragoza (Zaragoza)]]"
sitio_web: ""
portal_academico: ""
tags:
  - Universidad
---
## Perfil Institucional
Nodo de la Red Española de Supercomputación con el superordenador Agustina, gestionado a través del Instituto de Biocomputación y Física de Sistemas Complejos (BIFI).

## Grupos de Investigación, Laboratorios y Centros Mixtos
*(Centros singulares o laboratorios específicos adscritos o vinculados a esta universidad)*

| **Centro / Laboratorio** | **Línea de Investigación Principal** | **Nodos Tecnológicos** |
| ------------------------ | ------------------------------------- | ----------------------- |
| Nodo Agustina (BIFI) | Supercomputación / RES | [[Red Española de Supercomputación (RES)]] |

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
