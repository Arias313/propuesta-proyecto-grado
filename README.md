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

## Zona XY - Análisis  

**Zona XY** es un proyecto orientado a la **compra y venta de consolas, videojuegos y accesorios gamer**.  
Su propósito principal es brindar una experiencia de compra **rápida, segura y confiable en Medellín**, con la posibilidad de realizar **envíos a nivel nacional**.  

Más que una tienda online, Zona XY busca convertirse en un **espacio para la comunidad gamer**, donde los clientes encuentren sus consolas favoritas, accesorios y juegos, con la garantía de un servicio cercano y eficiente.  

Con el fin de anticipar posibles dificultades y fortalecer la planeación del negocio, se elaboró un **diagrama de Ishikawa**, en el que se identifican las principales causas y subcausas que podrían generar fallas o baja eficiencia en el futuro.


![Diagrama Ishikawa Zona XY](https://raw.githubusercontent.com/Arias313/propuesta-proyecto-grado/img/Diagrama%20de%20ishikawa%20ZonaXY.png)


---

## 👤 Ficha de Usuario (User Persona)

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

## Historial de Usuario (Resumen)

| ID  | Usuario       | Historia                                         | Prioridad | Riesgo | Puntos | Iteración | Responsable       |
|-----|---------------|--------------------------------------------------|-----------|--------|--------|-----------|-------------------|
| 001 | Cliente       | Ver catálogo de consolas y accesorios disponibles | Alta      | Bajo   | 3      | 1         | Juan David Arias  |
| 002 | Cliente       | Comprar consola y seleccionar método de entrega   | Alta      | Medio  | 5      | 1         | Juan David Arias  |
| 003 | Administrador | Actualizar inventario y ver estadísticas de ventas| Alta      | Alto   | 5      | 2         | Juan David Arias  |

---

# V&V en Proyecto Zona XY

---

## Requisito
> “El sistema debe permitir a los administradores actualizar el inventario de consolas y videojuegos en tiempo real.”

| **Verificación (Consistencia)** | **Validación (Necesidad Real)** |
|---------------------------------|----------------------------------|
| Se detecta una **inconsistencia técnica**: el sistema actual de la tienda solo sincroniza el inventario **cada hora** con el proveedor logístico, por lo que “en tiempo real” no es viable. Esto evidencia un **error de especificación** o una **falsa expectativa del cliente**.<br><br>**Conclusión:** el requisito no es verificable como está escrito. Debe revisarse antes de pasar a desarrollo. | En las entrevistas iniciales con los administradores se observa que, aunque desean actualizaciones “rápidas”, realmente lo que necesitan es **evitar vender productos agotados**, no necesariamente un sistema en tiempo real. Esto muestra una **confusión en la necesidad real del usuario**.<br><br>**Conclusión:** se requiere redefinir la necesidad antes de ajustar el diseño técnico. |

---

## Requisito
> “El sistema debe generar reportes automáticos de ventas diarios y enviarlos por correo electrónico a todos los empleados.”

| **Verificación (Consistencia)** | **Validación (Necesidad Real)** |
|---------------------------------|----------------------------------|
| Durante la revisión de requerimientos se identifica un **error de alcance**: no todos los empleados deben recibir reportes de ventas. Según las políticas de la empresa, solo el **equipo administrativo** y **gerencia** tienen acceso a dicha información. Además, el requisito no especifica el formato ni los parámetros del reporte.<br>
<br>**Conclusión:** fallo de **verificación**. El requisito carece de precisión y contradice las normas internas de confidencialidad. | En la reunión de validación, los usuarios finales comentan que no necesitan recibir reportes diarios, ya que el exceso de correos genera **sobrecarga de información**. Lo que realmente requieren es un **panel de consulta semanal** y la opción de exportar reportes bajo demanda.<br><br>**Conclusión:** fallo de **validación**. La funcionalidad propuesta no se ajusta a la necesidad real del usuario. |

---

## Conéctate conmigo
[![YouTube](https://img.shields.io/badge/YouTube-Canal-red?logo=youtube&logoColor=white)](https://youtube.com/@juandavidarias8585?si=dX1dl-Sm-z124RiX)
[![Instagram](https://img.shields.io/badge/Instagram-@ariasjd313-purple?logo=instagram&logoColor=white)](https://www.instagram.com/ariasjd313/?next=%2F)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-blue?logo=linkedin&logoColor=white)](#)
[![X](https://img.shields.io/badge/Twitter-@miusuario-1DA1F2?logo=twitter&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-Arias313-black?logo=github)](https://github.com/Arias313)

✉ Email: **ja0249837@gmail.com**

