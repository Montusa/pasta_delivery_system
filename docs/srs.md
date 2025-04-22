# Especificación de Requerimientos del Sistema (SUJETO A CAMBIOS)
## Requerimientos Funcionales
El sistema:

1. Debe permitir registrar un nuevo pedido.
2. debe permitir seleccionar múltiples platos por pedido.
3. Debe permitir tener opciones personalizables para cada plato.
4. Debe registrar la fecha y hora de entrega elegida por el cliente.
5. Debe poder mostrar todos los pedidos registrados al usuario.
6. Debe validar que la fecha y hora de entrega de un pedido sea al menos 48 horas posterior al momento de su creación. En caso contrario, no debe permitir registrarlo.

## Requerimientos No Funcionales

1. La interfaz debe estar diseñada de manera que todos los formularios y controles necesarios para registrar un pedido puedan visualizarse y completarse sin necesidad de hacer scroll en una pantalla de resolución 1366x768 píxeles.
2. Los datos deben almacenarse de forma persistente en una base de datos relacional, permitiendo su recuperación completa incluso después de reiniciar la aplicación.
3. El código del sistema debe estar alojado en un repositorio de GitHub, utilizando control de versiones con commits descriptivos y diferenciación de ramas por funcionalidades.
4. Toda funcionalidad implementada debe estar documentada mediante comentarios en el código y descripciones en archivos README o documentos específicos dentro del repositorio.
