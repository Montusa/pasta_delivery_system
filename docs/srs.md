# Especificación de Requerimientos del Sistema (SUJETO A CAMBIOS)
## Requerimientos Funcionales
El sistema:

1. Debe permitir registrar un nuevo pedido.
2. Debe permitir seleccionar múltiples platos por pedido.
3. Debe permitir tener opciones personalizables para cada plato.
4. Debe registrar la fecha y hora de entrega elegida por el cliente.
5. Debe poder mostrar todos los pedidos registrados al usuario.
6. Debe validar que la fecha y hora de entrega de un pedido sea al menos 48 horas posterior al momento de su creación. En caso contrario, no debe permitir registrarlo.
7. Debe asociar un estado a cada pedido. Puede tomar uno de los siguientes: "No empezado", "En proceso", "Listo para entregar" o "Entregado".
8. Debe permitir cambiar el estado de un pedido únicamente siguiendo el siguiente orden secuencial: "No empezado" → "En proceso" → "Listo para entregar" → "Entregado".
9. No debe permitir retroceder a estados anteriores ni saltar etapas.
10. Debe bloquear la modificación del estado de un pedido después de ser marcado como "Entregado".
11. Debe registrar la forma de pago seleccionada para cada pedido: "tarjeta de crédito", "tarjeta de débito" o "efectivo". Con las formas de crédito y débito se sobreentiende que el pago se hizo en el momento del registro del pedido.


## Requerimientos No Funcionales

1. La interfaz debe estar diseñada de manera que todos los formularios y controles necesarios para registrar un pedido puedan visualizarse y completarse sin necesidad de hacer scroll en una pantalla de resolución 1366x768 píxeles.
2. Los datos deben almacenarse de forma persistente en una base de datos relacional, permitiendo su recuperación completa incluso después de reiniciar la aplicación.
3. El código del sistema debe estar alojado en un repositorio de GitHub, utilizando control de versiones con commits descriptivos y diferenciación de ramas por funcionalidades.
4. Toda funcionalidad implementada debe estar documentada mediante comentarios en el código y descripciones en archivos README o documentos específicos dentro del repositorio.


## Consideraciones Generales
Este documento está sujeto a cambios durante el proceso de desarrollo. Toda modificación debe registrarse mediante un commit en el repositorio, idealmente con un mensaje que haga referencia directa a la sección afectada.
