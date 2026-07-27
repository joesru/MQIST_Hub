---
aliases:
  - UC3M
tags:
  - Universidad
---

# Universidad Carlos III de Madrid (UC3M)

**📍 Ubicación:** [[Getafe (Madrid)]], [[Comunidad de Madrid]]

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
