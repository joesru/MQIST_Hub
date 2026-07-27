---
aliases:
  - UIB
  - Universitat de les Illes Balears
tags:
  - Universidad
---

# Universidad de las Islas Baleares (UIB)

**📍 Ubicación:** [[Palma (Illes Balears)]], [[Islas Baleares]]

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
