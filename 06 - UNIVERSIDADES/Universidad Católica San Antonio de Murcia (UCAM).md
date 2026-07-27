---
aliases:
  - UCAM
tags:
  - Universidad
---

# Universidad Católica San Antonio de Murcia (UCAM)

**📍 Ubicación:** [[Región de Murcia]]

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
