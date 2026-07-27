# 🏢 Panel de Control: Empresas e Instituciones

Este panel centraliza toda la información de las entidades guardadas en la carpeta `01 - EMPRESAS`, permitiéndote ver su información de contacto, sector y tu red de networking de un vistazo.

---

## 📇 1. Directorio General de Entidades
*Una tabla maestra con todas las empresas registradas, ideal para consultas rápidas de ubicación y enlaces a sus webs o redes.*

```dataview
TABLE 
    sectores AS "Sector", 
    tipo_entidad AS "Tipo",
    ubicaciones AS "Ubicación", 
    sitio_web AS "Web"
FROM "01 - EMPRESAS" OR #Empresa
WHERE file.name != "Plantilla_Empresas"
SORT file.name ASC
````

## 📊 2. Distribución por Sectores

```dataview
TABLE 
    length(rows) AS "Total Entidades",
    rows.file.link AS "Directorio de Empresas"
FROM "01 - EMPRESAS" OR #Empresa
WHERE sectores != null AND file.name != "Plantilla_Empresas"
GROUP BY sector
SORT length(rows) DESC
```

## 🤝 3. Contactos por empresa
_Personas según la empresa en la que trabajan_

```dataview
TABLE 
    rows.file.link AS "Contactos Internos",
    rows.cargo AS "Cargos"
FROM "04 - CONTACTOS" OR #contacto
WHERE empresa != null AND file.name != "Plantilla_Contacto"
GROUP BY empresa
SORT length(rows) DESC
````
