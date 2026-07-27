---
tipo_entidad: Startup
sectores: Software Cuántico-Inspirado, Optimización y Finanzas
matriz: "[[Consejo Superior de Investigaciones Científicas (CSIC)]]"
tipo_relacion: ""
ubicaciones:
Dirección:
location:
sitio_web: ""
Linkedin:
telefono:
email:
tags:
  - Empresa
---
## Perfil de la entidad
*(Breve descripción de las líneas de actividad, mercado objetivo y relevancia estratégica de la organización)*

Inspiration-Q es una empresa de base tecnológica (startup) especializada en el desarrollo de soluciones de computación cuántica-inspirada, orientada fundamentalmente a los sectores de finanzas, logística y aprendizaje automático interpretable. Fundada por doctores en física y respaldada financieramente por el fondo de inversión Bullnet Capital, la compañía nace como una spin-off del [[Consejo Superior de Investigaciones Científicas (CSIC)]]. Su ventaja competitiva reside en capitalizar más de dos décadas de investigación académica en tecnologías cuánticas para trasladarlas a aplicaciones de negocio a corto plazo, democratizando el acceso a estas herramientas de alto rendimiento sin depender de la madurez del hardware cuántico universal.

El modelo de negocio de Inspiration-Q se estructura en la provisión de algoritmos de optimización empaquetados como Software as a Service (SaaS). Estas herramientas están diseñadas desde cero para imitar el comportamiento de los sistemas cuánticos, lo que permite resolver problemas combinatorios de enorme complejidad matemática de manera nativa en infraestructuras de supercomputación clásica y en la nube. Con este enfoque, la empresa logra sortear las limitaciones actuales del hardware cuántico (como el ruido o la escasez de cúbits), aportando a sus clientes mejoras drásticas en velocidad computacional, ahorro de memoria y calidad de las soluciones globales frente a los optimizadores comerciales tradicionales.

A nivel de producto, la oferta de la compañía se divide en dos grandes suites. Por un lado, "iQ Finance", un ecosistema de herramientas dirigido a instituciones financieras para la creación de productos de inversión personalizados, la replicación de índices bursátiles con carteras muy reducidas de activos y la gestión híbrida pasivo-activa con filtros como liquidez o criterios ESG. Por otro lado, "iQ Xtreme", un motor de optimización matemática avanzado enfocado en resolver cuellos de botella transversales en la industria, tales como el diseño de redes de telecomunicaciones, la ubicación de instalaciones y la planificación eficiente de rutas en logística y transporte.

## Tecnologías y líneas de investigación / Áreas de trabajo
*(Lista de líneas de investigación y trabajo de la empresa con su descripción y con las empresas con las que colaboran en ese aspecto)*

| **Línea de trabajo**                                      | **Descripción (Incluye aquí los enlaces a los Nodos Tecnológicos en INGLÉS)**                                                                                                                                                                                                                                                                                                                                              | **Otras empresas asociadas**                                                                         |
| --------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| Algoritmia Cuántica-Inspirada y Cloud                     | Desarrollo de ecosistemas de [[Quantum-Inspired Computing]] que simulan los principios naturales de enfriamiento atómico y cristalización. Estos modelos operan mediante dinámicas globales de [[Simulated Annealing]] para evitar óptimos locales en la resolución de problemas. El software se distribuye en modelo [[Software as a Service]] ejecutándose sobre plataformas clásicas de [[Cloud Computing]] como Azure. | [[Consejo Superior de Investigaciones Científicas (CSIC)]], [[Bullnet Capital]], [[Microsoft Azure]] |
| Finanzas Cuantitativas y Gestión de Carteras (iQ Finance) | Uso de rutinas de [[Mathematical Optimization]] para el diseño de productos financieros mediante "Direct Indexing". Permite la replicación de grandes índices (ej. S&P 500) usando subconjuntos mínimos de activos, estrategias híbridas de generación de alfa, arbitraje y selección de fondos aplicando restricciones complejas como criterios ESG y riesgo sectorial combinados con [[Machine Learning]].               |                                                                                                      |
| Optimización Industrial y Logística (iQ Xtreme)           | Implementación de solvers algorítmicos para superar problemas NP-Hard en entornos industriales. Aplicación directa en el cálculo y diseño de redes eléctricas y de telecomunicaciones, enrutamiento de vehículos y optimización de cadenas de suministro (Transport and Facility Location Optimization).                                                                                                                   |                                                                                                      |

## Sedes y centros de trabajo
*(Oficinas, laboratorios, observatorios, talleres...)*

| **LOCALIDAD (Provincia)** | **Tipo de sede** | **Dirección** |
| -------------------------- | ----------------- | -------------- |
| [[Madrid (Madrid)]] | Sede central y base de desarrollo tecnológico de la spin-off | Madrid, España |

## Contactos dentro de la empresa
*(Tabla rápida de referencia; la ficha completa de cada persona vive en 04 - CONTACTOS)*

| **Nombre y Apellidos** | **Puesto** | **Email** | **Teléfono** | **Enlace Linkedin** |
| ----------------------- | ---------- | --------- | ------------ | -------------------- |
|                         |            |           |              |                      |
|                         |            |           |              |                      |
|                         |            |           |              |                      |

## Fuentes consultadas

- Inspiration-Q (https://inspiration-q.com/company)
- Inspiration-Q - FAQs (https://inspiration-q.com/faqs)
- Inspiration-Q - iQ Finance (https://inspiration-q.com/products/iq-finance)
- Inspiration-Q - iQ Index Tracking (https://inspiration-q.com/products/iq-index-tracking)
- Inspiration-Q - iQ Index Tracking Plus (https://inspiration-q.com/products/iq-index-tracking-plus)
- Inspiration-Q - iQ Xtreme (https://inspiration-q.com/products/iq-xtreme)
- Inspiration-Q - Solutions: Help create financial products (https://inspiration-q.com/solutions/help-create-financial-products)
- Inspiration-Q - Solutions: Help manage portfolios efficiently (https://inspiration-q.com/so

---
## Histórico de ofertas y estado de candidaturas

```dataview
TABLE
    puesto AS "Puesto",
    ubicacion AS "Localización",
    fecha_publicacion AS "Publicada",
    cv_enviado AS "CV Enviado",
    fase AS "Fase",
    resultado AS "Resultado"
FROM "02 - OFERTAS"
WHERE contains(empresa, this.file.link)
SORT fecha_publicacion DESC
```

## Contactos vinculados (vía Dataview)
*(Se rellena solo a partir de las notas en 04 - CONTACTOS que apunten a esta empresa)*

```dataview
TABLE
    cargo AS "Cargo",
    email AS "Email",
    telefono AS "Teléfono",
    linkedin AS "LinkedIn"
FROM "04 - CONTACTOS"
WHERE contains(empresa, this.file.link)
SORT file.name ASC
```
