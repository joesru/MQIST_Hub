---
aliases:
  - "AWS"
  - "Amazon Web Services, Inc."
tipo_entidad: "Empresa Privada"
sectores:
  - "Tecnologia"
  - "Cuántica"
  - "I+D-Investigacion"
  - "Consultoria"
matriz: "Amazon.com, Inc."
tipo_relacion: ""
ubicaciones:
  - "Seattle (Washington)"
  - "Pasadena (California)"
  - "Madrid (Madrid)"
Dirección: "Seattle, WA, USA"
location:
sitio_web: "https://aws.amazon.com/braket/"
Linkedin: "https://www.linkedin.com/company/amazon-web-services/"
telefono: ""
email: "quantum-bd@amazon.com"
tags:
  - Empresa
---
## Perfil de la entidad

Amazon Web Services (AWS) es el proveedor de infraestructura en la nube líder a nivel mundial, ofreciendo más de 200 servicios integrales de centros de datos. En el ámbito de las tecnologías profundas, AWS ha desarrollado una estrategia integral para democratizar el acceso a la computación cuántica a través de su plataforma en la nube, la investigación fundamental en hardware y la consultoría especializada. Su objetivo es proporcionar a investigadores, desarrolladores y empresas las herramientas necesarias para diseñar algoritmos cuánticos, probarlos en simuladores de alto rendimiento y ejecutarlos en una variedad de procesadores cuánticos (QPU) de terceros sin necesidad de inversiones iniciales en hardware físico.

**Ejes estratégicos de actuación:**
*   **Amazon Braket (Quantum as a Service):** Es el servicio completamente administrado de AWS que sirve como puerta de entrada a la computación cuántica. Permite a los usuarios acceder a una multiplicidad de backends de hardware (superconductores, iones atrapados y átomos neutros) mediante un único kit de desarrollo de software (SDK) agnóstico, compatible también con marcos de código abierto como [[PennyLane]], [[Qiskit]] y [[CUDA-Q]].
*   **Simulación de circuitos y flujos híbridos:** AWS Braket ofrece simuladores bajo demanda (SV1 para [[State Vector Simulation]], DM1 para matrices de densidad con modelado de ruido, y TN1 para redes tensoriales). Además, facilita la ejecución de *Hybrid Jobs*, que orquestan flujos de trabajo cuántico-clásicos de baja latencia utilizando contenedores integrados, ideal para algoritmos variacionales como [[Quantum Approximate Optimization Algorithm (QAOA)]] y [[Variational Quantum Eigensolver (VQE)]].
*   **AWS Center for Quantum Computing:** Un centro de investigación y desarrollo propio radicado en el campus de la [[California Institute of Technology (Caltech)]] en [[Pasadena (California)]]. Aquí, científicos de AWS investigan arquitecturas de hardware tolerantes a fallos basadas en [[Superconducting Qubits]], desarrollando chips experimentales como el "Ocelot", centrado en la corrección de errores cuánticos bosónicos, y avanzando en protocolos de destilación e interconexión.
*   **Amazon Advanced Solutions Lab:** Un programa de servicios profesionales e investigación colaborativa donde expertos cuánticos de AWS asisten a clientes empresariales en la identificación de casos de uso viables en sus industrias, combinando aprendizaje automático clásico, optimización y prototipado cuántico.

**Hitos y alianzas clave:**
La estrategia de AWS se basa fundamentalmente en alianzas con los principales proveedores de hardware del mundo para alojarlos en su nube. A través de Braket, AWS proporciona acceso a los sistemas superconductores de [[IQM]] (Garnet, Emerald) y [[Rigetti]] (Ankaa, Cepheus), a los ordenadores de iones atrapados de [[IonQ]] (Aria, Forte) y [[AQT]] (IBEX-Q1), y a los procesadores de átomos neutros de [[QuEra Computing]] (Aquila), habilitando en este último el paradigma de [[Analog Hamiltonian Simulation]]. Además, AWS colabora profundamente con firmas de software y middleware cuántico como [[Classiq]], [[ColdQuanta]], [[Pasqal]], [[Q-CTRL]], [[QC Ware]] y [[Strangeworks]] para integrar sus soluciones de mitigación de errores, compilación y control a nivel de pulso.

**Investigación conjunta por institución:**
*   **[[California Institute of Technology (Caltech)]]:** Alberga las instalaciones físicas del AWS Center for Quantum Computing, colaborando en el diseño y fabricación de dispositivos superconductores e investigación teórica en [[Quantum Error Correction]].
*   **[[Institute for Quantum Computing (IQC)]] (Universidad de Waterloo):** Colaboración académica para explorar ventajas algorítmicas y preparar la infraestructura canadiense para el despliegue de soluciones híbridas en la nube.
*   **[[CINECA]] y el [[Istituto Nazionale di Fisica Nucleare (INFN)]]:** Utilizan AWS Braket para acelerar la investigación científica en Italia, entrenando modelos algorítmicos aplicables a la física de altas energías.
*   **[[Massachusetts Institute of Technology (MIT)]]**, **[[Carnegie Mellon University]]**, **[[Columbia University]]**, **[[Johns Hopkins University]]**, **[[University of Washington]]**: Centros integrados en la red global de *Science Hubs* de Amazon, impulsando la investigación conjunta no solo en inteligencia artificial, sino también en las intersecciones con ciencias físicas y de la información cuántica.

**Ecosistema industrial/comunidad:**
El ecosistema de clientes de Braket y el *Advanced Solutions Lab* es vasto e incluye a gigantes corporativos explorando ventajas a largo plazo. [[Volkswagen Group]] utiliza el servicio para optimizar procesos industriales (Binary paint shop); el [[BMW Group]] colabora en la optimización de trayectorias de robots; [[Amgen]] evalúa la viabilidad de la simulación cuántica para el descubrimiento de fármacos; [[Enel]] prueba técnicas de optimización para la planificación de recursos energéticos; y [[Aioi Nissay Dowa Insurance]] desarrolla clasificadores basados en redes neuronales cuánticas para telemática automotriz.

**Conexiones con España:**
El ecosistema general de AWS tiene un impacto directo y masivo en España, con una región de infraestructura de nube operativa en **Aragón** y oficinas centrales corporativas en **[[Madrid (Madrid)]]**. En relación estricta a las tecnologías cuánticas y de I+D, el portal oficial de empleo de Amazon ha registrado de manera activa vacantes asociadas al desarrollo de software y criptografía en España. Además, los grupos de investigación universitarios españoles pueden acceder a los recursos cuánticos de Braket a través del programa **AWS Cloud Credit for Research**, el cual financia pruebas de concepto y simulaciones algorítmicas, conectando el talento local con la infraestructura cuántica global operada por AWS.

Profesionalmente, AWS representa uno de los entornos corporativos más potentes para el desarrollo de carrera en *Deep Tech*. Sus procesos de selección buscan desde investigadores predoctorales hasta ingenieros de hardware de fabricación (salas blancas y criogenia en su laboratorio de Pasadena) y desarrolladores de compiladores cuánticos. El enfoque hacia la nube exige perfiles que comprendan la integración entre la infraestructura clásica escalable (HPC, AWS Batch, EC2) y los aceleradores cuánticos remotos.

## Tecnologías y líneas de investigación / Áreas de trabajo

| **Línea de trabajo** | **Descripción (con enlaces técnicos en INGLÉS)** | **Otras empresas asociadas** |
| --------------------- | ---------------- | ----------------------------- |
| Plataforma Quantum-as-a-Service | Desarrollo y mantenimiento de Amazon Braket, que ofrece orquestación de recursos cuánticos, ejecución sin servidor mediante *Hybrid Jobs* y acceso a simuladores clásicos de gran escala. | [[PennyLane]], [[Qiskit]], [[NVIDIA]] |
| Fabricación de Hardware Cuántico | Diseño de chips experimentales, procesos de litografía y control de señales de microondas en entornos de criogenia bajo el paradigma de [[Superconducting Qubits]]. | [[California Institute of Technology (Caltech)]] |
| Sistemas Híbridos y Optimización | Implementación de algoritmos variacionales como [[Quantum Approximate Optimization Algorithm (QAOA)]] y rutinas de [[Quantum Machine Learning]] para resolver problemas logísticos y de química. | [[BMW Group]], [[Volkswagen Group]], [[QC Ware]] |
| Simulación de Circuitos (HPC) | Desarrollo de emuladores integrados de alto rendimiento empleando [[State Vector Simulation]] y [[Tensor Network]] sobre infraestructura de supercomputación nativa de AWS. | [[NVIDIA]], [[PennyLane]] |
| Criptografía y Seguridad | Investigación y despliegue de protocolos seguros para servicios en la nube, integrando evaluación de riesgos algorítmicos e implementaciones de [[Post-Quantum Cryptography]]. | Sin información detallada |

## Sedes y centros de trabajo

| **LOCALIDAD (Provincia)** | **Tipo de sede** | **Dirección** |
| -------------------------- | ----------------- | -------------- |
| [[Seattle (Washington)]] | Sede Central Corporativa (AWS HQ) | Seattle, WA, USA |
| [[Pasadena (California)]] | AWS Center for Quantum Computing (R&D Lab) | Campus de la California Institute of Technology, Pasadena, CA |
| [[Madrid (Madrid)]] | Sede Regional corporativa | Madrid, España |

## Contactos dentro de la empresa

| **Nombre y Apellidos** | **Puesto** | **Email** | **Teléfono** | **Enlace Linkedin** |
| ----------------------- | ---------- | --------- | ------------ | -------------------- |
| Fernando Brandão | Amazon Scholar / Quantum Scientist | quantum-bd@amazon.com | Sin información | Sin información |
| Oskar Painter | Quantum Hardware Scientist (AWS Center for Quantum Computing) | quantum-bd@amazon.com | Sin información | Sin información |
| Ryan Shaffer | Quantum Research Scientist | Sin información | Sin información | Sin información |
| Alexander Dalzell | Quantum Research Scientist | Sin información | Sin información | Sin información |
| Yunong Shi | Applied Scientist, Quantum | Sin información | Sin información | Sin información |

## Perfiles y vacantes habituales

| **Puesto / Rol** | **Área** | **Nivel** | **Enlace al portal de empleo** |
| ----------------- | -------- | --------- | -------------------------------- |
| Quantum Research Scientist | Applied Science | Senior / PhD | https://www.amazon.jobs/en |
| Applied Scientist, Quantum Algorithms | Algorithms / Software | Senior | https://www.amazon.jobs/en |
| Machinist, Quantum Computing | Hardware / Fabrication | Indiferente | https://www.amazon.jobs/en |
| Buyer - Quantum Hardware | Procurement / Supply Chain | Indiferente | https://www.amazon.jobs/en |
| Quantum Hardware Engineer, Device | Hardware Development | Junior / Senior | https://www.amazon.jobs/en |
| Security Engineer, Services Cryptography | Seguridad / Cloud | Senior | https://www.amazon.jobs/en |

## Fuentes consultadas
* https://aws.amazon.com/braket/
* https://aws.amazon.com/braket/quantum-computers/
* https://aws.amazon.com/braket/features/
* https://aws.amazon.com/braket/pricing/
* https://aws.amazon.com/braket/faqs/
* https://docs.aws.amazon.com/braket/latest/developerguide/what-is-braket.html
* https://www.amazon.science/research-areas/quantum-technologies
* https://www.amazon.science/academic-engagements
* https://www.quantumjobs.us/company/amazon
* https://github.com/amazon-braket/amazon-braket-sdk-python
* https://aws.amazon.com/advanced-solutions-lab/

