# Product Backlog inicial

Cada requisito funcional se traduce en una historia de usuario. Es la base de las tarjetas del tablero de Trello.

| ID | Historia de usuario | Criterios de aceptación | Prioridad | Sprint |
| --- | --- | --- | --- | --- |
| RF01 | Como recepcionista quiero registrar, consultar y editar los datos de un cliente para tener su información disponible al recibir un equipo | Se guardan nombre, teléfono y correo; no se permite guardar sin los datos obligatorios; los cambios se reflejan al consultar | Alta | 2 |
| RF02 | Como recepcionista quiero registrar un equipo y asociarlo a un cliente para saber a quién pertenece | Todo equipo queda vinculado a un cliente existente; se registran marca, modelo y número de serie | Alta | 2 |
| RF03 | Como recepcionista quiero crear una orden de servicio con la falla reportada para iniciar la reparación y entregar un comprobante al cliente | La orden queda asociada a un cliente y a un equipo; se genera un comprobante con número de orden y fecha | Alta | 2 |
| RF04 | Como recepcionista quiero asignar un técnico a cada orden para saber quién la repara | Cada orden tiene un técnico asignado; el técnico ve las órdenes que le corresponden | Alta | 3 |
| RF05 | Como técnico quiero actualizar el estado de la reparación para que el taller sepa en qué etapa va | Estados permitidos: Recibido, En diagnóstico, En reparación, Listo y Entregado; cada cambio queda registrado con fecha y usuario | Alta | 3 |
| RF06 | Como dueño del taller quiero consultar el historial por cliente y por equipo para conocer las reparaciones anteriores | El historial muestra las órdenes y los cambios de estado; permite filtrar por cliente y por equipo | Media | 3 |
| RF07 | Como administrador quiero que cada usuario acceda con usuario y contraseña según su rol para proteger la información | Sin iniciar sesión no se accede a ninguna función; cada rol solo ve las funciones permitidas | Alta | 1 y 2 |

## Requisitos no funcionales

| Código | Requisito | Prioridad |
| --- | --- | --- |
| RNF01 | Usabilidad: pantallas sencillas que se aprendan en poco tiempo | Media |
| RNF02 | Seguridad: solo los usuarios autorizados acceden a cada función | Alta |
| RNF03 | Compatibilidad con los navegadores web más usados | Media |

## Permisos por rol

| Rol | Funciones permitidas |
| --- | --- |
| Administrador | Gestionar usuarios y roles; consultar clientes, equipos, órdenes, historial y reporte de órdenes por estado |
| Recepcionista | Registrar y editar clientes y equipos; crear órdenes y comprobantes; asignar técnicos; consultar historial |
| Técnico | Ver las órdenes asignadas y actualizar su estado; consultar el historial del equipo |

## Fuera del alcance

Facturación, inventario de repuestos, pagos en línea, aplicación móvil y notificaciones automáticas a los clientes.

*Fuente: Informe FixIt, Módulo II (Tablas 6 y 7) y Anexo B.*
