
# Hugo Onofre  
**Platform Engineering & Distributed Systems**  
*Ingeniero de Sistemas con enfoque en infraestructura crítica, sistemas distribuidos y gestión de operaciones.*

---

## Core Stack

| Categoría       | Tecnologías                                                                                     |
|-----------------|-------------------------------------------------------------------------------------------------|
| **Lenguajes**   | ![C++](https://img.shields.io/badge/C++-17-blue?logo=cplusplus) ![Node.js](https://img.shields.io/badge/Node.js-20-green?logo=nodedotjs) ![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python) |
| **Infraestructura** | ![Linux](https://img.shields.io/badge/Linux-Ubuntu%20Server-FCC624?logo=linux) ![Docker](https://img.shields.io/badge/Docker-24-blue?logo=docker) ![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?logo=gnubash) |
| **Data & Geoespacial** | ![MySQL](https://img.shields.io/badge/MySQL-8-orange?logo=mysql) ![PostGIS](https://img.shields.io/badge/PostGIS-3-green?logo=postgresql) |
| **Plataforma**  | ![Kubernetes](https://img.shields.io/badge/K8s-1.28-blue?logo=kubernetes) ![Terraform](https://img.shields.io/badge/Terraform-1.5-purple?logo=terraform) |

---

## Current Mission  
**Arquitectura de vigilancia epidemiológica distribuida – Secretaría de Salud (México)**  
Lidero el diseño e implementación de un sistema de monitoreo en tiempo real para malaria, basado en una arquitectura geoespacial con MySQL y servicios de localización.

**Automation:** Pipelines Bash + Node.js para ingesta desde zonas rurales con conectividad intermitente (rsync + validación checksum).  
**Scalability:** Particionamiento horizontal de tablas MySQL por región epidemiológica; índices espaciales (R-tree) para consultas en datasets >1M registros.  
**Impacto:** Reducción del 30% en latencia de consolidación de datos y mejora en capacidad de respuesta operativa.

---

## Engineering Labs  
*Exploración profunda de sistemas y bajo nivel*

### Slab Allocator en C++  
Implementación de un asignador de memoria tipo *slab* para escenarios de alta concurrencia, aplicando RAII, gestión manual de memoria y optimización de fragmentación.  
*Benchmarks internos muestran reducción del 40% en overhead comparado con malloc.*

### Linux Toolkits  
Conjunto de utilidades en Bash, C++ y Python para administración de sistemas.  
**Observability:** Módulos en Python que recolectan métricas de procesos, latencia de I/O y análisis de logs con rotación automática.  
**Automation:** Scripts para provisioning idempotente de servidores Ubuntu y backups diferenciales.

---

## Platform Engineering en Práctica

| Principio | Implementación |
|-----------|----------------|
| **Observability** | Scripts Python con exportación de métricas JSON; seguimiento de latencia en operaciones geoespaciales. |
| **Automation** | Pipelines Bash + Node.js para despliegue continuo y orquestación de backups. |
| **Scalability** | Particionamiento horizontal de MySQL + índices espaciales para consultas eficientes. |
| **Infraestructura como Código** | Definición de entornos con Docker Compose y scripts idempotentes. |

---

## Visualización Técnica

### Métricas de Actividad
*El desarrollo es continuo y orientado a la reproducibilidad.*

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Hugonofre7&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Hugonofre7&layout=compact&theme=dark&hide_border=true)

### Diagrama de Referencia – Sistema de Vigilancia
Flujo de datos: `[Clínica rural] → [API Gateway Node.js] → [Procesamiento espacial PostGIS] → [Agregación de conglomerados] → [Dashboard epidemiológico]`.  
*Diagrama completo disponible en el [repositorio del proyecto](https://github.com/Hugonofre7/epidemiological-surveillance).*

---

## Gobernanza de Código Abierto

Todo el código público en mi perfil se publica bajo licencias que fomentan la colaboración y la adopción industrial:

- **Apache 2.0** – para proyectos de infraestructura crítica (Slab Allocator, Linux Toolkits).
- **MIT** – para utilidades, scripts de automatización y prototipos.

Cada repositorio incluye su archivo `LICENSE` correspondiente.

---

## Filosofía Técnica  
*“Big picture con raíces en el kernel.”*  
Mi experiencia en gestión de operaciones me permite traducir necesidades de negocio en arquitecturas robustas, mientras que mi práctica constante en C++ y Linux asegura que puedo descender al nivel de sistema cuando la confiabilidad lo exige.

---

*Perfil en construcción – próximos repositorios: controlador de dispositivos en Linux y simulador de partición distribuida.*
