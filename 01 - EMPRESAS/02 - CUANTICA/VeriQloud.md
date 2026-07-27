---
aliases:
  - "Qasmat"
  - "Qline"
  - "QEnclave"
  - "HyQloud"
tipo_entidad: "Startup"
sectores:
  - "Cuántica"
  - "Tecnologia"
  - "I+D-Investigacion"
  - "Consultoria"
matriz: ""
tipo_relacion: ""
ubicaciones:
  - "Montrouge (Francia)"
  - "París (Francia)"
  - "Montreal (Canadá)"
Dirección: "13 rue Victor Hugo, 92120 Montrouge, France"
location:
sitio_web: "http://veriqloud.com"
Linkedin: "https://www.linkedin.com/company/veriqloud"
telefono: ""
email: "kaplan@veriqloud.fr"
tags:
  - Empresa
---
## Perfil de la entidad

[[VeriQloud]] es una startup tecnológica y consultora fundada en París en 2017 por el Dr. Marc Kaplan (CEO), la Prof. Elham Kashefi (Chief Scientist Officer) y el Prof. Josh Nunn (Scientific Advisor). La compañía se dedica al desarrollo de soluciones de ciberseguridad avanzada y software cuántico, con el objetivo de preparar a las empresas para la era cuántica y anticipar las disrupciones que esta tecnología provocará en la protección de la información. Su enfoque "full-stack" abarca desde el diseño de hardware de comunicaciones hasta el desarrollo de aplicaciones y arquitecturas de red, proporcionando seguridad incondicional a largo plazo frente a amenazas futuras, incluidos los ataques de tipo "Store Now, Break Later" (almacenar ahora, descifrar después) procedentes de ordenadores cuánticos a gran escala.

**Ejes y pilares estratégicos:**
La estrategia tecnológica de VeriQloud se fundamenta en tres productos y arquitecturas clave:
*   **Comunicaciones Seguras en Tránsito (Qline):** Una arquitectura de red cuántica de área local (LAN) concebida como el "ethernet de la comunicación cuántica". Permite integrar nodos intermedios de manera rentable sin necesidad de adquirir equipamiento completo de [[Quantum Key Distribution]], facilitando la distribución de estados entrelazados y el establecimiento de claves criptográficas multiparte.
*   **Protección de Datos en Reposo (Qasmat):** Un sistema de almacenamiento distribuido no local que utiliza el esquema de [[Secret Sharing]] de Shamir. Este software divide los archivos en fragmentos cifrados que se distribuyen en una red de servidores, garantizando disponibilidad y seguridad extrema incluso si varios nodos son comprometidos. Está programado en Rust para maximizar el rendimiento y es compatible con orquestadores como [[Docker Swarm]] o [[Kubernetes]].
*   **Computación Cuántica Segura (QEnclave y HyQloud):** Entornos de ejecución confiable (Trusted Execution Environments) respaldados por más de 15 años de investigación en [[Blind Quantum Computing]]. Estas soluciones permiten a los clientes delegar cálculos complejos en ordenadores cuánticos alojados en la nube o en centros de datos sin revelar ni los datos de entrada, ni el algoritmo, ni los resultados obtenidos.

**Hitos y alianzas clave:**
VeriQloud ha logrado hitos experimentales de gran relevancia global, como la demostración exitosa de protocolos de [[Blind Quantum Computing]] multicliente verificable sobre su arquitectura Qline, así como la implementación pionera de protocolos de [[Quantum Oblivious Transfer]] y tokens cuánticos sobre hardware QKD real sin modificar los componentes fotónicos. A nivel de ecosistema y software abierto, han publicado `hw_sim`, un emulador de pila completa en [[GitHub]] que reproduce el comportamiento de hardware cuántico para facilitar a investigadores el desarrollo de aplicaciones sobre redes de comunicaciones cuánticas. La empresa ha sido seleccionada por la aceleradora [[Creative Destruction Lab]] (CDL-Toronto) en su vertical cuántico y es un miembro muy activo de la red europea [[Quantum Business Network]] (QBN).

**Investigación conjunta por institución:**
*   **[[Université Côte d'Azur]] y [[CNRS]] (I3S/INPHYNI):** Diseño y prueba del protocolo MULTISS, un sistema de almacenamiento seguro a largo plazo distribuido sobre múltiples redes QKD remotas. Emplea un esquema de compartición de secretos jerárquico basado en la interpolación de Birkhoff, mejorando la seguridad del protocolo previo LINCOS para resistir el compromiso total de subredes QKD y ciberataques a las líneas clásicas.
*   **[[Sorbonne Université]] y [[LIP6]]:** Desarrollo de pruebas de seguridad en el marco de la Criptografía Abstracta para protocolos de compartición de secretos aditivos sobre la arquitectura Qline, logrando la distribución de información sin el incremento lineal de recursos tradicional de las redes QKD.
*   **[[Sapienza Università di Roma]]:** Colaboración pionera en la implementación experimental de la computación cuántica ciega (BQC) distribuida multicliente. Mediante enlaces fotónicos de fibra, han logrado verificar cálculos en servidores cuánticos remotos partiendo de fuentes de estados no confiables, sentando las bases para el aprendizaje automático federado y seguro (Federated [[Quantum Machine Learning]]).

**Ecosistema industrial y comunidad:**
VeriQloud desempeña un papel de liderazgo en el consorcio europeo [[Quantum Internet Alliance]] (QIA), financiado por programas como Horizon 2020 y Horizon Europe de la Comisión Europea. Dentro del "Use Case Team" de QIA, la empresa colabora íntimamente con instituciones como [[SURF]] para promover la participación de usuarios finales, perfilar casos de uso de la internet cuántica y traducir esas necesidades empresariales (en sectores como banca, sanidad o defensa) en requisitos de sistemas de red. Además, VeriQloud es una entidad consultora activa en proyectos paraguas de la red QBN, como el benchmarking de ordenadores cuánticos (DIN SPEC) y el proyecto SQuaD de comunicaciones cuánticas en Alemania.

**Conexiones con España:**
A pesar de su gran proyección europea y su participación activa en consorcios transnacionales fuertemente dotados como la [[Quantum Internet Alliance]] (donde comparten ecosistema general con entidades españolas), no se ha localizado presencia física, oficinas corporativas, ni consorcios de investigación bilateral con universidades o instituciones estrictamente radicados en España en las fuentes proporcionadas. Su estructura operativa principal se divide entre Francia (París/Montrouge) y Canadá (Montreal).

Para profesionales del ámbito tecnológico, VeriQloud ofrece un entorno de trabajo privilegiado en la frontera absoluta entre la ciberseguridad clásica, la ingeniería de software (Cloud/Rust/C++) y la física cuántica. La empresa permite a desarrolladores de software y hardware involucrarse en la creación de los cimientos de la futura internet cuántica, con acceso a investigación puntera y colaboraciones internacionales en el desarrollo de protocolos criptográficos incondicionalmente seguros.

## Tecnologías y líneas de investigación / Áreas de trabajo

| **Línea de trabajo** | **Descripción (con enlaces técnicos en INGLÉS)** | **Otras empresas asociadas** |
| --------------------- | ---------------- | ----------------------------- |
| Secure Data-at-Rest / Almacenamiento Distribuido | Desarrollo del sistema Qasmat y el protocolo MULTISS para el almacenamiento a largo plazo, fragmentando datos mediante [[Secret Sharing]] jerárquico (Shamir y Birkhoff) a través de múltiples redes protegidas por [[Quantum Key Distribution]]. | [[Université Côte d'Azur]], [[CNRS]] |
| Quantum Communication Networks (Qline) | Diseño de infraestructuras de red fotónica local que simplifican el establecimiento de claves y permiten ejecutar primitivas avanzadas como [[Quantum Oblivious Transfer]] y tokens cuánticos sin la sobrecarga total de hardware de los sistemas QKD convencionales. | [[Sorbonne Université]], [[LIP6]] |
| Blind Quantum Computing & Cloud Security | Implementación de entornos QEnclave que garantizan la ejecución privada de algoritmos en servidores cuánticos remotos mediante [[Blind Quantum Computing]]. Facilita el desarrollo de esquemas multicliente seguros aplicables al [[Quantum Machine Learning]] federado. | [[Sapienza Università di Roma]], [[Sorbonne Université]] |
| Emulación de Hardware Cuántico de Red | Desarrollo de herramientas de simulación de código abierto (`hw_sim`) empaquetadas en [[Docker]] para replicar el comportamiento de las redes cuánticas y facilitar a la comunidad el testeo de protocolos y aplicaciones de red (como el cálculo del Qubit Error Rate). | Sin información |

## Sedes y centros de trabajo

| **LOCALIDAD (Provincia)** | **Tipo de sede** | **Dirección** |
| -------------------------- | ----------------- | -------------- |
| [[Montrouge (Francia)]] | Sede Principal y Oficinas Centrales | 13 rue Victor Hugo, 92120 Montrouge, France |
| [[París (Francia)]] | Laboratorios / Presencia Corporativa (Île-de-France) | Paris, Île-de-France 75014, FR |
| [[Montreal (Canadá)]] | Oficina Internacional | Rue Drummond, Montreal, Quebec, CA |

## Contactos dentro de la empresa

| **Nombre y Apellidos** | **Puesto** | **Email** | **Teléfono** | **Enlace Linkedin** |
| ----------------------- | ---------- | --------- | ------------ | -------------------- |
| Marc Kaplan | Chief Executive Officer (CEO) & Co-founder | kaplan@veriqloud.fr | Sin información | https://fr.linkedin.com/in/kapmarc |
| Elham Kashefi | Chief Scientist Officer & Co-founder | elham.kashefi@lip6.fr | Sin información | https://uk.linkedin.com/in/elham-kashefi-76b9286 |
| Josh Nunn | Scientific Advisor & Co-founder | Sin información | Sin información | Sin información |
| Anne Marin | Investigadora | marin@veriqloud.fr | Sin información | Sin información |
| Ruben Cohen | Software Developer | Sin información | Sin información | Sin información |
| Georg Harder | Quantum Photonics Engineer | Sin información | Sin información | Sin información |
| Chin-Te Liao | Quantum Simulation Engineer | Sin información | Sin información | Sin información |
| Patricia Grof | Cloud Engineer | Sin información | Sin información | Sin información |
| Philippe Fischer | Empleado | Sin información | Sin información | Sin información |
| Edgard Pierre | Empleado | Sin información | Sin información | Sin información |

## Perfiles y vacantes habituales

| **Puesto / Rol** | **Área** | **Nivel** | **Enlace al portal de empleo** |
| ----------------- | -------- | --------- | -------------------------------- |
| Internship at Veriqloud's hardware development team | Hardware / Fotónica Cuántica | Prácticas | https://quantuminternetalliance.org/vacancy/internship-at-veriqlouds-hardware-development-team/ |
| Cloud Engineer | Ingeniería de Software / Sistemas | Indiferente | Sin información |
| Software Developer | Desarrollo de Software | Indiferente | Sin información |

## Fuentes consultadas
* Prévost, T., Alibart, O., Marin, A., & Kaplan, M. (2024). MULTISS: a protocol for long-term secure distributed storage over multiple remote QKD networks.
* Grilo, A. B., Hanouz, L., & Marin, A. (2025). Security of a secret sharing protocol on the Qline. Sorbonne Université / VeriQloud.
* Braun, J., et al. (2017). LINCOS - A Storage System Providing Long-Term Integrity, Authenticity, and Confidentiality.
* Polacchi, B., et al. (2025). Experimental Verifiable Multiclient Blind Quantum Computing on a Qline Architecture. Phys. Rev. Lett., 134, 200603. DOI: 10.1103/PhysRevLett.134.200603.
* Polacchi, B., et al. (2023). Multi-client distributed blind quantum computation with the Qline architecture. Nature Communications. DOI: 10.1038/s41467-023-43617-0.
* Doosti, M., & Kaplan, M. (2020). Quantum Applications and Use Case Report (D4.1). Quantum Internet Alliance.
* Perfil corporativo de VeriQloud en LinkedIn (https://www.linkedin.com/company/veriqloud)
* Ficha de VeriQloud en Creative Destruction Lab (https://creativedestructionlab.com/companies/veriqloud/)
* Ficha de VeriQloud en la Quantum Internet Alliance (https://quantuminternetalliance.org/veriqloud/)
* Repositorio hw_sim en GitHub de VeriQloud (https://github.com/Veriqloud/hw_sim)
* Blog de ingeniería: "Ansible Automation for Secure Persistent Storage on Docker Swarm" por Patricia Grof.
* Portal de QBN - Quantum Business Network (https://qbn.world/qbn-member/veriqloud/)