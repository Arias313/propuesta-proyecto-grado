#  Juan David Arias 愛 - Perfil en GitHub

[![Estudiante](https://img.shields.io/badge/Role-Estudiante-blue)]()
[![Lenguaje](https://img.shields.io/badge/Java-Basic-green)]()
[![Status](https://img.shields.io/badge/Activo%20en%20GitHub-✔-brightgreen)]()

**Soy estudiante de Tecnología en Desarrollo de Software**.  
Me gusta la programación, los videojuegos y la creación de proyectos prácticos para seguir aprendiendo.  

Actualmente trabajo en:
- 🎮 Un juego rompe-ladrillos en Unity.  
- 🌐 Una página web en HTML + CSS.  
- 🎓 Proyecto base para entrega final de grado.  

---

## Sobre mí
Me gusta aprender sobre tecnologías nuevas, experimentar en diversos campos y proyectos de tecnología.  
También tengo interés en negocios y el sector agrícola para futuros proyectos personales.  

---

## Tecnologías que manejo
- **Lenguajes:** Java, JavaScript, SQL, Python  
- **Frontend:** HTML, CSS  
- **Herramientas:** Git, GitHub, VS Code, Unity, TurboWarp  

---

## Repositorios Destacados
- [Rompe-ladrillos en Unity](#)  
- [Renta de autos - HTML/CSS](#)  
- [Estadística aplicada en Python](#)  

---

# Proyecto Zona XY – Gestión de Requerimientos

## 📑 Contenido
1. [Introducción](#1-introducción)
2. [Técnicas de recolección](#2-técnicas-de-recolección)
3. [Ciclo de vida de desarrollo](#3-ciclo-de-vida-de-desarrollo)
4. [Diagrama de Ishikawa](#4-diagrama-de-ishikawa)
5. [User Persona](#5-user-persona)
6. [Historias de Usuario](#6-historias-de-usuario)
7. [Verificación y Validación (V&V)](#7-verificación-y-validación-vv)
8. [Requisitos funcionales](#8-requisitos-funcionales)
9. [Requisitos no funcionales](#9-requisitos-no-funcionales)
10. [Diagrama de procesos](#10-diagrama-de-procesos-opcional)
11. [Gestión de requerimientos – Jira](#11-gestión-de-requerimientos--jira)
12. [Conclusiones](#12-conclusiones)
13. [Bibliografía](#13-bibliografía)

---

## 1. Introducción
### 1.1 Contexto
Zona XY es un emprendimiento local dedicado a la compra y venta de consolas, videojuegos y accesorios gamer.

### 1.2 Problema
La ausencia de procesos digitalizados dificulta la trazabilidad del inventario, genera pérdidas por errores en el manejo de stock y limita el alcance comercial.

### 1.3 Objetivo
Desarrollar un sistema que apoye la gestión de inventario, ventas y clientes, mejorando la eficiencia operacional y la trazabilidad del negocio.

---

## 2. Técnicas de recolección

Para la obtención de los requerimientos del sistema de Zona XY, se emplearon diversas técnicas de recolección de información:

| Técnica | Descripción | Hallazgos |
|--------|-------------|-----------|
| Entrevistas | Reuniones con dueño del negocio | Falta trazabilidad de inventario |
| Observación | Visita al punto físico | Procesos manuales y alta probabilidad de errores |
| Encuestas | Realizadas a clientes frecuentes | Interés en catálogo digital |
| Benchmark | Comparación con tiendas similares | Necesidad de ventas online |

---


## 3. Ciclo de vida de desarrollo

Se adopta un modelo **Ágil – Scrum**, debido a su adaptabilidad y enfoque incremental.

Fases:
- Creación de Product Backlog
- Sprint Planning
- Desarrollo iterativo
- Sprint Review
- Retrospectiva

---

## 4. Diagrama de Ishikawa  
Se analizan causas potenciales de fallas en el negocio:  
- **Métodos**: Control manual de productos  
- **Personas**: Falta de capacitación  
- **Maquinaria**: No existe software  
- **Materiales**: Registros físicos obsoletos  
- **Entorno**: Alta demanda sin proceso eficiente  

![Diagrama Ishikawa Zona XY](https://raw.githubusercontent.com/Arias313/propuesta-proyecto-grado/img/Diagrama%20de%20ishikawa%20ZonaXY.png)

---

## 5 User Persona

| Campo              | Información base                              |
|--------------------|-----------------------------------------------|
| **Nombre y apodo**  | Sebastián López - “El Gamer Retro”           |
| **Edad**           | 24 años                                       |
| **Ocupación**      | Estudiante universitario / Streamer           |
| **Ubicación**      | Medellín, Antioquia                           |
| **Nivel educativo**| Universitario en curso                        |
| **Ingreso mensual**| $1.000.000 COP (apoyo familiar + streaming)   |


### Descripción
> Sebastián es un jugador apasionado que combina videojuegos modernos con coleccionismo retro. Usa plataformas online para buscar consolas nuevas y de segunda a buen precio, y valora la rapidez en las entregas.
> Prefiere tiendas confiables, con buena atención al cliente y métodos de pago simples.

### Objetivos
- Comprar consolas nuevas y usadas con garantía.  
- Recibir pedidos de forma rápida en Medellín.  
- Encontrar accesorios gamer confiables a buen precio.  
- Hacer compras seguras sin complicaciones técnicas.

---

## 6. Historias de Usuario


| ID  | Usuario       | Historia                                         | Prioridad | Riesgo | Puntos | Iteración | Responsable       |
|-----|---------------|--------------------------------------------------|-----------|--------|--------|-----------|-------------------|
| 001 | Cliente       | Ver catálogo de consolas y accesorios disponibles | Alta      | Bajo   | 3      | 1         | Juan David Arias  |
| 002 | Cliente       | Comprar consola y seleccionar método de entrega   | Alta      | Medio  | 5      | 1         | Juan David Arias  |
| 003 | Administrador | Actualizar inventario y ver estadísticas de ventas| Alta      | Alto   | 5      | 2         | Juan David Arias  |

---

## 7. Verificación y Validación (V&V)

### Ejemplo 1  
> **Requisito:** El sistema debe actualizar inventario en tiempo real.  

| Verificación | Validación |
|--------------|------------|
| No viable, depende del proveedor, no cumple precisión | No es real necesidad; se busca evitar ventas sin stock |

---

## 8. Requisitos funcionales

- RF1: Gestionar inventario  
- RF2: Registrar ventas  
- RF3: Consultar catálogo  
- RF4: Registrar clientes  

---

## 9. Requisitos no funcionales

- RNF1: Tiempo de carga < 2s  
- RNF2: Disponibilidad 90%  
- RNF3: Compatible con móviles  
- RNF4: Seguridad de datos  

---

## 10. Diagrama de procesos (Opcional)
> (Espacio para BPMN o flujo)

---

## 11. Gestión de requerimientos – Jira

Se configuró Jira con un tablero Kanban donde se asignaron historias de usuario, se les dio prioridad y se realizó seguimiento de su desarrollo en iteraciones simuladas.

Se documentó:  
- Historias de usuario  
- Prioridades  
- Flujo Kanban  
- Cierre de tareas  

---

## 12. Conclusiones

- Se estructuró correctamente el proceso de requerimientos  
- Se identificaron necesidades reales  
- Se definieron historias de usuario verificables  
- Se aplicó V&V para asegurar calidad  
- Se construyó documentación clara para desarrollo  

---

## 13. Bibliografía

- Sommerville, Ingeniería de Software  
- ISO/IEC 25000  
- Atlassian Jira Docs  

---

---
## Conéctate conmigo
[![YouTube](https://img.shields.io/badge/YouTube-Canal-red?logo=youtube&logoColor=white)](https://youtube.com/@juandavidarias8585?si=dX1dl-Sm-z124RiX)
[![Instagram](https://img.shields.io/badge/Instagram-@ariasjd313-purple?logo=instagram&logoColor=white)](https://www.instagram.com/ariasjd313/?next=%2F)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-blue?logo=linkedin&logoColor=white)](#)
[![X](https://img.shields.io/badge/Twitter-@miusuario-1DA1F2?logo=twitter&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-Arias313-black?logo=github)](https://github.com/Arias313)


✉ Email: **ja0249837@gmail.com**

---
