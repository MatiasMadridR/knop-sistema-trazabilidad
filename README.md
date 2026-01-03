# KNOP DigitalFab – Sistema de Digitalización de Planillas de Producción

Proyecto de título desarrollado a partir de una necesidad real detectada en KNOP Laboratorios S.A. (Quilpué), orientado a la digitalización de las planillas de fabricación de medicamentos, con énfasis en trazabilidad, control de procesos y cumplimiento normativo.

---

## Contexto
En la planta de producción de KNOP, la mayoría de la documentación del proceso productivo se realiza mediante planillas físicas en papel.  
Si bien este enfoque cumple con las exigencias normativas, genera múltiples dificultades operativas como:

- Errores en el registro manual de datos
- Tiempos elevados en la consolidación de información
- Falta de acceso a datos en tiempo real
- Dificultades en auditorías internas y externas
- Riesgos en cuanto a la pérdida o deterioro de documentación histórica

---

## Objetivo del proyecto
Diseñar e implementar un sistema interno que permitiera:

- Digitalizar las planillas de fabricación y envasado
- Centralizar la información del proceso productivo
- Mejorar la trazabilidad de cada lote fabricado
- Reducir errores de registro mediante validaciones automáticas
- Facilitar auditorías y revisiones de calidad
- Asegurar cumplimiento de las Buenas Prácticas de Manufactura (BPM)

---

## Solución implementada
Se desarrolló una aplicación web interna, operativa dentro de la red del laboratorio, accesible desde computadores y tablets en planta.

El sistema permite registrar digitalmente cada etapa del proceso productivo, asociando cada acción a un usuario, fecha y hora, incorporando flujos de validación y firma electrónica simple para las aprobaciones correspondientes.

La solución fue diseñada considerando desde su origen los requerimientos normativos del Instituto de Salud Pública (ISP) y la legislación chilena sobre documentos electrónicos.

---

## Rol y responsabilidades
Mi participación en el proyecto incluyó:

- Levantamiento de requerimientos en planta (entrevistas y observación directa)
- Análisis de procesos productivos y documentación BPM
- Diseño de la arquitectura de la solución
- Modelamiento de datos orientado a trazabilidad
- Desarrollo del sistema web
- Definición de validaciones, flujos de aprobación y control de estados
- Apoyo en la definición de indicadores operativos (KPI)

---

## Enfoque en datos y procesos
Más allá del desarrollo de software, el foco principal del proyecto estuvo en:

- La correcta estructuración de los datos de producción
- La trazabilidad por lote y etapa del proceso
- El control de integridad y versionado de la información
- La disponibilidad de datos históricos para análisis operativo y auditorías

Este enfoque es una base para futuras integraciones con sistemas como MES, ERP o LIMS.

---

## Tecnologías utilizadas
- Python
- Django
- MySQL
- HTML, CSS, JavaScript
- Bootstrap / Tailwind CSS
- ReportLab (generación de documentos)
- Arquitectura web interna (on-premise)

---

## Impacto del proyecto
La implementación del sistema permite proyectar mejoras como:

- Reducción significativa de errores de registro
- Disminución de tiempos de validación de lotes
- Eliminación del uso de papel en procesos críticos
- Mayor disponibilidad y confiabilidad de la información
- Mejor preparación frente a auditorías internas y regulatorias

---

## Nota sobre el código
Por tratarse de un sistema interno de uso productivo y regulado, el código fuente completo no se encuentra publicado.

Este repositorio tiene como objetivo presentar el contexto del problema, el enfoque de la solución y las decisiones técnicas adoptadas durante el proyecto.
