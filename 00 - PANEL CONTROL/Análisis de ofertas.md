## 🏆 1. Ranking Completo de Entidades (Top Empleadores)
*Muestra qué empresas u organismos están publicando más ofertas que encajan con tu perfil, ordenadas de mayor a menor volumen de contratación.*

```dataview
TABLE 
    length(rows) AS "Total Ofertas", 
    rows.sector[0] AS "Sector Principal"
FROM "02 - OFERTAS"
WHERE empresa != null
GROUP BY empresa
SORT length(rows) DESC
```
## 🔬 2. Ranking de Sectores y Áreas de Investigación
_Indica hacia dónde se está moviendo el dinero y la necesidad de talento (ej. Cuántica, Aceleradores de partículas, Espacio, IA)._

```dataview
TABLE 
    length(rows) AS "Volumen de Demanda",
    rows.empresa AS "Entidades Contratantes"
FROM "02 - OFERTAS"
WHERE sector != null
GROUP BY sector
SORT length(rows) DESC
```

## 💻 3. Ranking de Habilidades y Tecnologías Demandadas
_Extrae todas las etiquetas tecnológicas (tags) de las ofertas y las cuenta. Te dirá si el mercado pide más Python, Qiskit, Machine Learning, o instrumentación electrónica._

```dataview
TABLE 
    length(rows) AS "Frecuencia de aparición"
FROM "02 - OFERTAS"
FLATTEN file.tags AS Etiqueta
WHERE Etiqueta != "#Oferta" AND Etiqueta != "#contacto" AND Etiqueta != "#entidad"
GROUP BY Etiqueta
SORT length(rows) DESC
````


## 💶 4. Radar de Oportunidades Financiadas (I+D+i Público)
_Rastrea qué programas de financiación gubernamental o europea están inyectando fondos para contratación (ej. Proyecto QUORUM, Quantum Spain)._

```dataview
TABLE 
    puesto AS "Puesto Financiado", 
    empresa AS "Entidad Ejecutora",
    fecha_limite AS "Deadline"
FROM "02 - OFERTAS"
WHERE programa_financiacion != null
SORT fecha_limite ASC
````
