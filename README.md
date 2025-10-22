
## V&V en Proyecto Zona XY.

### Requisito Base:
> “El sistema debe permitir a los administradores actualizar el inventario de consolas y videojuegos en tiempo real.”

| **Verificación (Consistencia)** | **Validación (Necesidad Real)** |
|---------------------------------|----------------------------------|
| Durante la revisión de los requerimientos se detecta una contradicción con las políticas de la tienda: el sistema solo sincroniza datos de inventario **cada hora**, no en tiempo real, debido a las limitaciones del proveedor logístico. <br><br>**Resultado:**  Fallo de **Verificación**. El requisito debe modificarse para reflejar la capacidad real del sistema: *el inventario se actualizará automáticamente cada hora o cuando se complete una venta.* | En la validación con el cliente se observa que los administradores necesitan **actualizaciones más inmediatas** para evitar vender productos agotados. <br><br>**Resultado:**  Fallo de **Validación**. Aunque el sistema funciona según lo planeado, no satisface la necesidad de **control y precisión**. Se ajusta para permitir una **actualización manual instantánea** desde el panel de administración cuando sea necesario. |
