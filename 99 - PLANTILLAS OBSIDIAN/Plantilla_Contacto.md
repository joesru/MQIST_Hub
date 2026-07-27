---
Nombre_Apellidos:
empresa:
cargo: ""
email: ""
telefono: ""
linkedin: ""
ofertas_vinculadas:
tags:
  - contacto
---
## Contexto y notas
*(Dónde o cómo nos conocimos, de qué hablamos, detalles clave a recordar o dudas que preguntarle).*


---
## Ofertas en las que ha intervenido este contacto

```dataview
TABLE
    puesto AS "Puesto",
    empresa AS "Empresa",
    fase AS "Fase",
    resultado AS "Resultado"
FROM "02 - OFERTAS"
WHERE contains(contacto, this.file.link)
SORT fecha_publicacion DESC
```
