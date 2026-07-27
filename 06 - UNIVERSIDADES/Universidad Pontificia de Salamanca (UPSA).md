---
aliases:
  - UPSA
tags:
  - Universidad
---

# Universidad Pontificia de Salamanca (UPSA)

**📍 Ubicación:** [[Castilla y León]]

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
