
## V&V en Proyecto Zona XY.



###  Requisito...
> “El sistema debe permitir a los administradores actualizar el inventario de consolas y videojuegos en tiempo real.”

| **Verificación (Consistencia)** | **Validación (Necesidad Real)** |
|---------------------------------|----------------------------------|
| Se detecta una **inconsistencia técnica**: el sistema actual de la tienda solo sincroniza el inventario **cada hora** con el proveedor logístico, por lo que “en tiempo real” no es viable. Esto evidencia un **error de especificación** o una **falsa expectativa del cliente**.<br><br>**Conclusión:** el requisito no es verificable como está escrito. Debe revisarse antes de pasar a desarrollo. | En las entrevistas iniciales con los administradores se observa que, aunque desean actualizaciones “rápidas”, realmente lo que necesitan es **evitar vender productos agotados**, no necesariamente un sistema en tiempo real. Esto muestra una **confusión en la necesidad real del usuario**.<br><br>**Conclusión:** se requiere redefinir la necesidad antes de ajustar el diseño técnico. |

---

###  Requisito..
> “El sistema debe generar reportes automáticos de ventas diarios y enviarlos por correo electrónico a todos los empleados.”

| **Verificación (Consistencia)** | **Validación (Necesidad Real)** |
|---------------------------------|----------------------------------|
| Durante la revisión de requerimientos se identifica un **error de alcance**: no todos los empleados deben recibir reportes de ventas. Según las políticas de la empresa, solo el **equipo administrativo** y **gerencia** tienen acceso a dicha información. Además, el requisito no especifica el formato ni los parámetros del reporte.<br><br>**Conclusión:** fallo de **verificación**. El requisito carece de precisión y contradice las normas internas de confidencialidad. | En la reunión de validación, los usuarios finales comentan que no necesitan recibir reportes diarios, ya que el exceso de correos genera **sobrecarga de información**. Lo que realmente requieren es un **panel de consulta semanal** y la opción de exportar reportes bajo demanda.<br><br>**Conclusión:** fallo de **validación**. La funcionalidad propuesta no se ajusta a la necesidad real del usuario. |

---

