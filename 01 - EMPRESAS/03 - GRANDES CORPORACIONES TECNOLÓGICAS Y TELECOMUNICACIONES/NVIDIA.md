---
aliases:
  - "NVIDIA Corporation"
tipo_entidad: "Empresa Privada"
sectores:
  - "Tecnologia"
  - "Cuántica"
  - "I+D-Investigacion"
matriz: ""
tipo_relacion: ""
ubicaciones:
  - "Estados Unidos"
Dirección: ""
location:
sitio_web: "https://www.nvidia.com/"
Linkedin: "https://www.linkedin.com/company/nvidia/"
telefono: ""
email: "privacy@nvidia.com"
tags:
  - Empresa
---
## Perfil de la entidad

NVIDIA es un líder mundial indiscutible en el diseño de unidades de procesamiento gráfico y plataformas de computación acelerada e Inteligencia Artificial. En los últimos años, la compañía ha pivotado agresivamente hacia el sector de las tecnologías cuánticas con la creación de la plataforma integral NVIDIA Quantum. Su misión en este ámbito no es construir hardware cuántico nativo (cúbits físicos), sino proporcionar la infraestructura de supercomputación clásica, la conectividad y el ecosistema de software necesarios para orquestar flujos de trabajo híbridos cuántico-clásicos, abordando cuellos de botella críticos como la corrección de errores en tiempo real y la simulación algorítmica a gran escala.

**Ejes estratégicos de actuación:**
*   **Simulación Cuántica de Alto Rendimiento:** Mediante el SDK cuQuantum, NVIDIA permite a los investigadores emular circuitos cuánticos y dinámicas de sistemas utilizando la potencia masiva de sus GPUs (como la arquitectura Blackwell y Hopper). Soporta métodos de vector de estado y redes tensoriales con capacidades multi-nodo para superar los límites del hardware cuántico físico actual (NISQ).
*   **Plataforma Híbrida Cuántica-GPU (CUDA-Q):** Un marco de desarrollo de código abierto (C++ y Python) que permite escribir y compilar aplicaciones que distribuyen automáticamente la carga de trabajo entre CPUs, GPUs y unidades de procesamiento cuántico (QPUs), integrándose estrechamente con la infraestructura HPC existente.
*   **Interconexión QPU-GPU (NVQLink):** Arquitectura de red de ultra baja latencia (<4.0 microsegundos) y alto rendimiento (400 Gb/s) diseñada para comunicar los controladores cuánticos (QSC) con los servidores acelerados por GPU, habilitando la corrección de errores cuánticos en tiempo real.
*   **Inteligencia Artificial para Cuántica (NVIDIA Ising):** Una familia de modelos fundacionales de IA (incluyendo modelos de visión-lenguaje y redes CNN 3D) de código abierto diseñados específicamente para automatizar la calibración ultrarrápida del hardware cuántico y acelerar la decodificación de síndromes de error.

**Hitos y alianzas clave:**
NVIDIA ha forjado alianzas de altísimo nivel para integrar su plataforma en la vanguardia científica. Un hito crítico es la asociación con el [[Oak Ridge National Laboratory (ORNL)]] y [[HPE]], donde instalarán un sistema basado en el superchip NVIDIA GB200 NVL72 conectado a los ordenadores cuánticos de [[IQM]] y [[Quantum Brilliance]] a través de NVQLink, sentando las bases de la supercomputación acelerada cuánticamente junto al superordenador Frontier. Además, en Europa, colaboran íntimamente con el [[Forschungszentrum Jülich]] para el superordenador exaescala JUPITER, impulsado por tecnología NVIDIA Grace Hopper y redes Quantum-X800 InfiniBand. En la industria aeroespacial, han logrado avances significativos junto a [[Rolls-Royce]] y [[Classiq]] en el uso de la computación cuántica para la dinámica de fluidos computacional en motores a reacción.

**Investigación conjunta por institución:**
*   **[[University of Toronto]]**: Desarrollo del algoritmo Generative Quantum Eigensolver (GQE), una nueva clase de algoritmos que utiliza [[Artificial Intelligence]] para optimizar el rendimiento y el diseño de circuitos.
*   **[[Yale University]]**: Creación de un modelo híbrido basado en la arquitectura *transformer* con un mecanismo de autoatención cuantizado, aplicado directamente a tareas de generación molecular.
*   **[[Chung Yuan Christian University]]**: Desarrollo de modelos de redes neuronales cuánticas ([[Quantum Machine Learning]]) para la predicción de irradiancia solar, logrando entrenamientos acelerados mediante CUDA-Q y cuDNN.
*   **[[University of Edinburgh]]**: Investigación de métodos eficientes de agrupamiento divisivo (*divisive clustering*) para grandes volúmenes de datos orientados a aceleradores cuánticos.
*   **[[University of Innsbruck]]**: Empleo de modelos de difusión algorítmica para sintetizar operaciones unitarias arbitrarias, convirtiéndolas en kernels nativos dentro de la plataforma CUDA-Q.
*   **[[Technion - Israel Institute of Technology]]**: Aceleración del desarrollo de aplicaciones cuánticas utilizando los superordenadores de escritorio NVIDIA DGX Spark.

**Ecosistema industrial/comunidad:**
La penetración de NVIDIA en la industria cuántica es profunda y abarca desde integradores de software hasta los principales fabricantes de hardware del mundo. Operan estrechamente con [[Google Quantum AI]] (escalando simulaciones de dinámicas analógicas a 40 cúbits en el superordenador Eos), [[IBM]], [[BMW Group]], y [[Bayer]]. En el frente de hardware emergente y corrección de errores, asisten y colaboran de forma constante con [[Quantinuum]], [[Infleqtion]], [[QuEra Computing]], [[Terra Quantum]], [[QMware]] y [[Anyon Technologies]]. Su programa NVIDIA Inception apoya además a un vasto número de *startups* cuánticas globales. 

**Conexiones con España:**
Tras revisar las fuentes corporativas y estratégicas proporcionadas, no se ha localizado presencia física directa de laboratorios cuánticos, centros de investigación o sedes corporativas de NVIDIA en España, más allá del soporte regional comercial y la disponibilidad web en español. Sin embargo, su tecnología GPU subyacente forma parte crítica de superordenadores europeos en los que España participa y del ecosistema híbrido que empresas como [[Centro de Supercomputación de Galicia (CESGA)]] emplean para escalar simulaciones.

Profesionalmente, hacer seguimiento a NVIDIA es imperativo para cualquier científico de datos, ingeniero de software de alto rendimiento o investigador cuántico. La compañía es el puente de facto entre el [[High Performance Computing]], la IA generativa y las QPUs experimentales. Dominar su pila tecnológica (CUDA-Q y cuQuantum) garantiza empleabilidad inmediata en casi cualquier centro de supercomputación mundial o empresa que busque hibridar algoritmos cuánticos con IA.

## Tecnologías y líneas de investigación / Áreas de trabajo

| **Línea de trabajo** | **Descripción (con enlaces técnicos en INGLÉS)** | **Otras empresas asociadas** |
| --------------------- | ---------------- | ----------------------------- |
| Plataforma de Software Cuántico-Clásico | Desarrollo de la plataforma de código abierto CUDA-Q (antes QODA) para la programación híbrida, compilación e integración fluida de QPUs, GPUs y CPUs en un mismo sistema usando un modelo de kernels. | [[Quantinuum]], [[Anyon Technologies]], [[QMware]] |
| Simulación de Circuitos y Redes Tensoriales | Kit de herramientas cuQuantum (incluye cuStateVec, cuTensorNet, cuDensityMat, cuPauliProp, cuStabilizer) para emular dinámicas hamiltonianas analógicas y algoritmos ruidosos empleando [[Quantum Simulation]]. | [[Google Quantum AI]], [[IBM]], [[Classiq]] |
| Interconexión QPU-GPU de ultra baja latencia | Desarrollo de la arquitectura NVQLink (usando RoCE, tarjetas ConnectX y FPGAs) que proporciona ruteo dinámico y un gran ancho de banda (400 Gb/s) para integrar control cuántico de manera nativa. | [[Oak Ridge National Laboratory (ORNL)]], [[HPE]], [[Infleqtion]] |
| Inteligencia Artificial para Cuántica | Creación de NVIDIA Ising, una familia de modelos de IA abiertos. Incluye Ising Calibration (modelo de visión-lenguaje) e Ising Decoding (CNNs 3D) para agilizar tareas críticas de [[Quantum Error Correction]]. | [[IQM]], [[Riverlane]] |
| Optimización Combinatoria y Machine Learning | Despliegue de algoritmos como el Variational Quantum Eigensolver (VQE), ADAPT-VQE y QAOA, combinando redes neuronales clásicas con kernels cuánticos (CUDA-QX) aplicados a química y logística. | [[Terra Quantum]], [[BMW Group]], [[Rolls-Royce]] |

## Sedes y centros de trabajo

| **LOCALIDAD (Provincia)** | **Tipo de sede** | **Dirección** |
| -------------------------- | ----------------- | -------------- |
| [[Estados Unidos]] | NVIDIA Accelerated Quantum Computing Research Center (NVAQC) | Sin información de dirección exacta en las fuentes |

## Contactos dentro de la empresa

| **Nombre y Apellidos** | **Puesto** | **Email** | **Teléfono** | **Enlace Linkedin** |
| ----------------------- | ---------- | --------- | ------------ | -------------------- |
| Jensen Huang | Chief Executive Officer (CEO) | privacy@nvidia.com | Sin información | Sin información |

## Perfiles y vacantes habituales

| **Puesto / Rol** | **Área** | **Nivel** | **Enlace al portal de empleo** |
| ----------------- | -------- | --------- | -------------------------------- |
| Sin información de vacantes específicas en las fuentes consultadas | | | |

## Fuentes consultadas
* https://developer.nvidia.com/cuda-quantum
* https://developer.nvidia.com/cuquantum-sdk
* https://www.nvidia.com/en-us/solutions/quantum-computing/nvqlink/
* https://www.nvidia.com/en-us/solutions/quantum-computing/ising/
* https://nvidia.github.io/cudaqx/components/qec/introduction.html
* https://nvidia.github.io/cudaqx/components/solvers/introduction.html
* https://developer.nvidia.com/blog/an-introduction-to-quantum-accelerated-supercomputing/
* https://www.nvidia.com/en-us/glossary/quantum-computing/
* Documento PDF: State-of-Quantum-2024-report.pdf
* Documento PDF: IQM-State-of-Quantum-2025.pdf
* Documento PDF: 2509.12949v1.pdf (First Practical Experiences Integrating Quantum Computers with HPC Resources)
* Documento PDF: 2510.26565v1.pdf (Tackling the Challenges of Adding Pulse-level Support to a Heterogeneous HPC