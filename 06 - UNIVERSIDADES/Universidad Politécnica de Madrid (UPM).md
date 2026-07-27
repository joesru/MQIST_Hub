---
aliases:
  - UPM
tags:
  - Universidad
---

# Universidad Politécnica de Madrid (UPM)

**📍 Ubicación:** [[Madrid (Madrid)]], [[Comunidad de Madrid]]

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
