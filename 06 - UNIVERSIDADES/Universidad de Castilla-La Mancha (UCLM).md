---
aliases:
  - UCLM
tags:
  - Universidad
---

# Universidad de Castilla-La Mancha (UCLM)

**📍 Ubicación:** [[Castilla-La Mancha]]

## 🏢 Relación en el Ecosistema
*(Proyectos, investigaciones o empresas vinculadas a esta universidad)*

```dataview
TABLE
    tipo_entidad AS "Tipo",
    sectores AS "Sectores",
    ubicaciones AS "Sedes"
FROM "01 - EMPRESAS"
WHERE contains(file.outlinks, this.file.link)
SORT file.name ASC
```
