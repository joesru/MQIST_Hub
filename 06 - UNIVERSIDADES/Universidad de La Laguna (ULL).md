---
aliases:
  - ULL
tags:
  - Universidad
---

# Universidad de La Laguna (ULL)

**📍 Ubicación:** [[Santa Cruz de Tenerife (Santa Cruz de Tenerife)]], [[Canarias]]

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
