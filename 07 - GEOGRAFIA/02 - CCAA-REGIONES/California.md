---
aliases:
Pais: "[[Estados Unidos]]"
Organismos_Publicos:
tags:
  - CCAA
---
## Descripción
*(Panorama tecnológico/institucional de la región: ecosistema de I+D, PERTEs activos, fondos FEDER relevantes)*


## Organismos Públicos y Programas de Financiación
*(Agencias de innovación, consejerías, fondos que operan en esta región)*

- 

---
## 📍 Localidades pertenecientes a esta región

```dataview
TABLE
    Pais AS "País"
FROM "07 - GEOGRAFIA/01 - LOCALIDADES"
WHERE contains(CCAA_Region, this.file.link)
SORT file.name ASC
```

## 🏢 Empresas con sede en esta región

```dataview
TABLE
    tipo_entidad AS "Tipo",
    sectores AS "Sectores",
    ubicaciones AS "Sede"
FROM "01 - EMPRESAS"
WHERE contains(ubicaciones, this.file.link)
SORT file.name ASC
```

## Provincias y Localidades

- **San Francisco**
  - [[San Francisco (San Francisco)]]

