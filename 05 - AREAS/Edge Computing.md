---
aliases:
  - Computación en el Borde
tags:
  - Area
---

## Descripción

Procesamiento de datos muy cerca del lugar donde se generan para lograr tiempos de respuesta mínimos.

## Áreas relacionadas

- [[Bioinformatics]]
- [[Classical Modeling and Infrastructures]]
- [[Cloud Computing]]
- [[Digital Twin]]
- [[Fuzzy Logic]]
- [[Geographic Information Systems]]
- [[Mathematical Optimization and Modeling]]
- [[Quantum Technologies]]
- [[Signal and Data Processing]]

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
```
