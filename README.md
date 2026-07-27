# 🌌 MQIST_Hub

**MQIST_Hub** es el espacio de trabajo, base de conocimiento y entorno de investigación integral orientado al **Máster en Ciencia y Tecnologías de Información Cuántica (MQIST)**, la física teórica/experimental y el desarrollo profesional en los sectores científico, aeroespacial y tecnológico.

Esta bóveda está diseñada bajo criterios de rigor científico, modularidad y código abierto, sirviendo como repositorio centralizado para apuntes académicos, mapeo del ecosistema industrial y seguimiento de oportunidades laborales e investigadoras.

# 👤 Autor y Propósito de la Bóveda

**Autor:** José Estepa Ruiz (Graduado en Física por la Universidad de Córdoba) — 🔗 [Perfil de LinkedIn](https://www.linkedin.com/in/jose-estepa-ruiz/)

Esta bóveda nace con un propósito estratégico muy claro: mapear, analizar y estructurar de forma rigurosa todo el ecosistema del sector de las tecnologías cuánticas y la industria tecnológica avanzada de cara al **Máster en Ciencia y Tecnologías de Información Cuántica (MQIST)**. 

El objetivo principal de este entorno de trabajo es anticiparse y tener absoluta claridad antes de arrancar el posgrado, permitiendo:
* Definir con criterio la **elección de asignaturas, módulos e itinerarios**.
* Identificar **líneas de investigación y grupos punteros** afines a los intereses académicos y profesionales.
* Trazar una estrategia sólida orientada a la selección de **prácticas de empresa** y a una óptima **inserción en el mercado laboral** especializado en el sector de alta tecnología.

---
# 📂 Estructura de la Bóveda

La información está organizada por la naturaleza de las entidades y por bloques académicos normalizados:

*   **`00 - PANEL CONTROL/`** — Paneles de control principales, hojas de ruta y análisis de ofertas.
*   **`01 - EMPRESAS/`** — Ecosistema industrial y científico categorizado por tipología:
    *   *01 - Instituciones Públicas, Agencias y Consorcios* (ESA, AEE, Ministerio de Defensa, etc.)
    *   *02 - Centros de Investigación, I+D+i y Supercomputación* (CERN, CSIC, CESGA, BSC, etc.)
    *   *03 - Grandes Corporaciones Tecnológicas y Telecomunicaciones* (IBM, Google, AWS, Telefónica, etc.)
    *   *04 - Industria: Aeroespacial, Defensa e Ingeniería* (Airbus, Navantia, Indra, Sener, etc.)
    *   *05 - Startups y Spin-offs (Deep-Tech y New Space)* (Quside, Qilimanjaro, IonQ, etc.)
    *   *06 - Consultoría y Servicios IT*
    *   *07 - Sector Financiero y Adoptantes*
*   **`02 - OFERTAS/`** — Historial y seguimiento de convocatorias, bolsas de empleo y ofertas del sector.
*   **`04 - CONTACTOS/`** — Directorio de profesores (MQIST, UCO) y redes de contacto profesionales.
*   **`05 - AREAS/`** — Notas atómicas y conceptuales sobre tecnologías habilitadoras, física cuántica, criptografía post-cuántica, machine learning y computación de altas prestaciones.
*   **`06 - UNIVERSIDADES/`** — Mapeo global de instituciones académicas de educación superior y física.
*   **`07 - GEOGRAFIA/`** — Ubicaciones, localidades y regiones estratégicas vinculadas a la red de I+D.
*   **`08 - MASTER MQIST/`** — Asignaturas estructuradas por semestres y módulos, itinerarios recomendados y bibliografía oficial del máster.
*   **`99 - PLANTILLAS OBSIDIAN/`** — Estructuras base normalizadas para la creación automatizada de notas.

---
# 🤖 Metodología de Creación e Inteligencia Aumentada

La generación de este volumen masivo de notas y la estructuración del conocimiento **no se ha realizado de forma puramente manual**. Para lograr un análisis profundo y exhaustivo, se ha diseñado un flujo de trabajo basado en **NotebookLM**:

1. **Cuadernos Especializados:** Se han generado múltiples cuadernos en NotebookLM (llegando hasta el límite máximo de fuentes permitidas por cuaderno), alimentándolos de forma sistemática con información técnica y oficial extraída directamente de los sitios web de cada empresa, planes docentes de asignaturas y perfiles de investigadores.
2. **Aplicación de Prompts Estrictos:** Todo el procesamiento y extracción de información se ha guiado mediante un conjunto de **prompts específicos y estrictos** orientados a mantener el rigor científico y la homogeneidad en los datos. Los archivos de texto originales de estos prompts (`prompt empresas.txt` y `prompt asignatura y profesor.txt`) se conservan en la raíz de esta bóveda como parte de la infraestructura metodológica.
3. **Descubrimiento Acelerado:** Este sistema ha permitido descubrir empresas emergentes, tecnologías de vanguardia, consorcios y líneas de investigación que, mediante una búsqueda manual convencional, habrían pasado desapercibidas o habrían requerido un coste temporal inasumible.

---
# 📁 Guía de Configuración Local y Uso de la Bóveda MQIST_Hub en Obsidian

Esta guía detalla los pasos para clonar, configurar y gestionar localmente la bóveda de Obsidian **MQIST_Hub**, asegurando la persistencia de los datos, la compatibilidad con plugins comunitarios y el control de versiones con Git.

### 1. Requisitos Previos en tu Equipo Local
Antes de clonar la bóveda, asegúrate de tener instalado en tu sistema:
* **Obsidian**: Para la lectura, edición y renderizado de las notas Markdown y LaTeX.
* **Git**: Para el control de versiones y la sincronización con el repositorio remoto.

### 2. Clonar el Repositorio en Local
Para descargar una copia exacta de la bóveda en tu equipo local (por ejemplo, en tu unidad `D:\`):

1. Abre tu terminal (PowerShell o Git Bash).
2. Navega hasta la ruta donde deseas alojar la carpeta (ej. `cd D:\`).
3. Ejecuta el comando de clonación:
   
   `git clone https://github.com/joesru/MQIST_Hub.git`

Esto creará la carpeta local `MQIST_Hub` con toda la estructura de directorios, notas y la configuración oculta de Obsidian.

### 3. Apertura de la Bóveda en Obsidian

Para que Obsidian reconozca la carpeta como una bóveda estructurada:

1. Abre la aplicación de **Obsidian**.
2. En la pantalla de gestión de bóvedas, haz clic en **"Open folder as vault"** (Abrir carpeta como bóveda).
3. Selecciona la carpeta recién clonada (`MQIST_Hub`).

### 4. Carga de Plugins y Entorno Visual

La bóveda incluye preconfigurada la carpeta oculta `.obsidian`, lo que garantiza que el entorno se replique de forma idéntica sin necesidad de instalación manual:

- **Plugins Comunitarios**: Se cargarán automáticamente (como *Dataview*, *LaTeX Suite*, *Calendar*, etc.). Si Obsidian te solicita confirmación de seguridad la primera vez, haz clic en **"Trust author and enable"** para habilitarlos.
- **Apariencia y CSS**: Los temas visuales y los fragmentos CSS personalizados se aplicarán al instante.

### 5. Gestión Local y Sencilla con Git (Flujo Diario)

Para mantener tus apuntes locales respaldados y sincronizados con GitHub tras cada sesión de estudio o investigación:

1. Abre tu terminal en la raíz de la bóveda.
2. Prepara los cambios locales:
   `git add .`
3. Registra los cambios con un mensaje descriptivo:
   `git commit -m "Actualización: Nuevos apuntes y notas locales"`
4. Sube la información a la nube:
   `git push`

> **Nota de Privacidad Local:** Los archivos sensibles, historiales de currículums (`03 - CV/`) y los estados locales de las ventanas se mantienen estrictamente en tu equipo gracias al archivo `.gitignore`, evitando filtraciones o conflictos innecesarios en el repositorio compartido.
