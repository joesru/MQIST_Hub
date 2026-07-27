---
aliases:
CCAA_Region: "[[Abruzos]]"
Pais: "[[Italia]]"
tags:
  - Localidad
---
## Descripción
*(Notas rápidas sobre el peso tecnológico de esta localidad: clústeres, parques científicos, campus, etc.)*


## Organismos Públicos relevantes
*(Agencias, consejerías o entes regionales/locales con competencia directa aquí)*

- 

---
## 🏢 Empresas ubicadas en esta localidad

```dataview
TABLE
    tipo_entidad AS "Tipo",
    sectores AS "Sectores"
FROM "01 - EMPRESAS"
WHERE contains(ubicaciones, this.file.link)
SORT file.name ASC
```

## 🎓 Universidades y centros académicos en esta localidad

```dataview
TABLE
    tipo_entidad AS "Tipo",
    financiacion AS "Financiación"
FROM "06 - UNIVERSIDADES"
WHERE contains(ubicaciones, this.file.link)
SORT file.name ASC
```
