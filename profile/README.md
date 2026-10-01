<div align="center">

# Área de Desarrollo — FCAV

**Facultad de Contabilidad y Administración**
Desarrollo y operación de los sistemas web institucionales

[![Sistemas](https://img.shields.io/badge/sistemas-38-2563eb?style=flat-square)](https://github.com/Desarrollo-de-software-FCAV)
[![Servidores](https://img.shields.io/badge/servidores-6-2563eb?style=flat-square)](https://github.com/Desarrollo-de-software-FCAV)
[![Repos](https://img.shields.io/badge/repos-12-0ea5e9?style=flat-square)](https://github.com/Desarrollo-de-software-FCAV)

</div>

---

## Qué hacemos

Mantenemos los sistemas web que usan la comunidad universitaria: portal institucional,
plataformas de inscripción, control escolar, biblioteca, almacén, y el asistente virtual
**CALI** con búsqueda semántica sobre la normativa de la facultad.

Trabajamos sobre infraestructura **Windows Server con IIS**, con un nodo dedicado a
procesamiento de lenguaje natural.

---

<div align="center">

## Arquitectura de la infraestructura

</div>

![Diagrama de la infraestructura del área de desarrollo](./diagrama-infraestructura.png)

<sub>Arquitectura verificada por inspección directa de los servidores en octubre de 2026.
Sin direcciones IP ni nombres de host por razones de seguridad.</sub>

---

## Cifras del área

<div align="center">

| | |
|:--|:--|
| **38** | aplicaciones web en producción |
| **6** | servidores operados |
| **9** | servicios de datos e inteligencia artificial |
| **17** | proyectos activos |
| **12** | repositorios |

</div>

---

## Proyectos

### Sistemas institucionales

| Proyecto | Descripción |
|---|---|
| Portal institucional | Punto de entrada público a los servicios de la facultad |
| Control escolar | Inscripción, asistencia y evaluación docente |
| Aspirantes | Proceso de ingreso y admisión |
| Biblioteca | Consulta de acervos, préstamos y tesis históricas |

### Plataforma y servicios

| Proyecto | Descripción |
|---|---|
| **CALI** | Asistente virtual institucional con búsqueda semántica (RAG) sobre normativa y documentos |
| Kioscos | Terminales táctiles distribuidos en campus |
| App móvil | Biblioteca y servicios al estudiante desde el dispositivo |
| Almacén | ERP de entradas, salidas y control de existencias |

### Operación

| Proyecto | Descripción |
|---|---|
| Bot de operaciones | ChatOps y SecOps, alertas de servicio y despliegue |
| Monitoreo | Vigilancia de recursos, servicios, puertos y certificados |
| Congreso | Plataforma del encuentro académico anual |

---

## Stack

<div align="center">

| Capa | Tecnología |
|---|---|
| **Servidor** | Windows Server · IIS |
| **Aplicaciones** | ASP.NET · ASP.NET Core |
| **Datos** | SQL Server · SQLite · base vectorial |
| **IA** | Microservicios de embeddings y clasificación de riesgos |
| **Clientes** | React · Node.js |
| **Operación** | Scripts de PowerShell · alertas en tiempo real |

</div>

---

## Cómo trabajamos

- **Un repositorio por sistema**, con su propio ciclo de vida
- **Entorno de pruebas dedicado** — nada llega a producción sin validarse antes
- **Documentación junto al código** — cada sistema explica qué es, dónde vive y qué depende de qué
- **Cambios registrados** — las alertas de despliegue quedan trazadas

---

<div align="center">

### ¿Consultas o-reportes de un sistema?

Abre un *issue* en el repositorio correspondiente.
Cada proyecto tiene su propio historial, así que el reporte llega directo a quien lo mantiene.

</div>

---

<div align="center">

<sub>Desarrollo de software · Facultad de Contabilidad y Administración</sub>

</div>
