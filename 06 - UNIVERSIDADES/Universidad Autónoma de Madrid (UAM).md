---
aliases:
  - UAM
tags:
  - Universidad
---

# Universidad Autónoma de Madrid (UAM)

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
