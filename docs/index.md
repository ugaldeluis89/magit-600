# Gestión del conocimiento en equipos SRE usando GitHub

Este sitio presenta un demo académico de cómo un repositorio GitHub puede estructurarse como un sistema de gestión del conocimiento (KMS) para un equipo de Site Reliability Engineering (SRE).

---

## ¿Qué demuestra este repositorio?

Este demo ilustra cómo integrar la gestión del conocimiento dentro del flujo operativo mediante:

- documentación reutilizable (runbooks)
- aprendizaje estructurado (postmortems)
- estándares de documentación
- validación mediante pull requests
- automatización con GitHub Actions

---

## Estructura del conocimiento

El conocimiento se organiza en cuatro áreas principales:

### 📘 Runbooks
Procedimientos operativos para la resolución de incidentes y tareas recurrentes  
👉 [Ver runbooks](runbooks/index.md)

### 📗 Postmortems
Análisis de incidentes y lecciones aprendidas  
👉 [Ver postmortems](postmortems/index.md)

### 📙 Standards
Lineamientos y criterios de documentación  
👉 [Ver standards](standards/index.md)

### 📕 Architecture
Modelo conceptual de gestión del conocimiento  
👉 [Ver arquitectura](architecture/index.md)

---

## Flujo de gestión del conocimiento

El modelo implementado sigue un flujo estructurado:

1. Se identifica un incidente o necesidad
2. Se documenta mediante templates
3. Se propone un cambio mediante pull request
4. Se valida automáticamente
5. Se aprueba y versiona el conocimiento
6. Se reutiliza en la operación

---

## Relación con SRE

Este enfoque permite:

- reducir la dependencia de conocimiento tácito
- mejorar la consistencia operativa
- acelerar la resolución de incidentes
- facilitar la colaboración entre zonas horarias
- disminuir el trabajo manual repetitivo (\textit{toil})

---

## Nota

Este sitio corresponde a un entorno de demostración.  
No contiene información sensible ni refleja sistemas productivos reales.