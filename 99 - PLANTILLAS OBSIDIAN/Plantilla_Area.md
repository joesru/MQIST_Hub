---
aliases:
  - 
tags:
  - Area
---
## Descripción


## Áreas relacionadas

- 

---

## 🏢 Empresas del Radar asociadas a este nodo
*(Organizaciones que trabajan o investigan en esta área)*

```dataview
TABLE
    tipo_entidad AS "Tipo",
    sectores AS "Sectores",
    ubicaciones AS "Sedes"
FROM "01 - EMPRESAS"
WHERE contains(file.outlinks, this.file.link)
SORT file.name ASC
````
