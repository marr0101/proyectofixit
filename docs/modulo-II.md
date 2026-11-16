# Resumen de alcance y requisitos funcionales (Módulo II)

## Alcance

FixIt es un sistema web simulado para planificar la gestión de servicios de un taller pequeño de reparación de computadoras y dispositivos electrónicos. El alcance funcional incluye la gestión de clientes y equipos, órdenes de servicio y comprobantes, asignación de técnicos, actualización de estados de reparación e historial de servicios. El sistema contempla los roles de administrador, recepcionista y técnico.

Quedan fuera del alcance la facturación, el inventario de repuestos, los pagos en línea, la aplicación móvil y las notificaciones automáticas a clientes. Este proyecto evidencia la planificación y gestión; no implica la programación completa del sistema.

## Requisitos funcionales

- **RF01 – Clientes:** registrar, consultar y editar clientes; requerir nombre, teléfono y correo.
- **RF02 – Equipos:** registrar equipos con marca, modelo y número de serie, vinculándolos a un cliente existente.
- **RF03 – Órdenes de servicio:** crear órdenes asociadas a cliente y equipo, y generar un comprobante con número de orden y fecha.
- **RF04 – Asignación de técnicos:** asignar un técnico a cada orden; cada técnico puede ver las órdenes que le corresponden.
- **RF05 – Estados de reparación:** permitir los estados Recibido, En diagnóstico, En reparación, Listo y Entregado; registrar cada cambio con fecha y usuario.
- **RF06 – Historial:** consultar el historial de órdenes y cambios de estado por cliente y por equipo.
- **RF07 – Acceso por roles:** requerir usuario y contraseña; impedir el acceso sin iniciar sesión y limitar las funciones según el rol.

El [Product Backlog](05-product-backlog.md) contiene las historias de usuario, criterios de aceptación, prioridades, sprints y requisitos no funcionales.

