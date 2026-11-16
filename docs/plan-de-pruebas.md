# Plan de pruebas (borrador)

Los casos se derivan de los criterios de aceptación del Product Backlog. Responsable del plan: Mariaelis. Pruebas funcionales: los tres integrantes.

Resultado: completar con Aprobado o Fallido al ejecutar cada caso.

| ID | Requisito | Caso de prueba | Resultado esperado | Rol | Resultado |
| --- | --- | --- | --- | --- | --- |
| CP01 | RF01 | Registrar un cliente con nombre, teléfono y correo | El cliente se guarda y aparece al consultarlo | Recepcionista | |
| CP02 | RF01 | Intentar guardar un cliente sin los datos obligatorios | El sistema no permite guardar y muestra un aviso | Recepcionista | |
| CP03 | RF01 | Editar los datos de un cliente existente | Los cambios se reflejan al consultar | Recepcionista | |
| CP04 | RF02 | Registrar un equipo con marca, modelo y número de serie asociado a un cliente | El equipo queda vinculado al cliente | Recepcionista | |
| CP05 | RF02 | Intentar registrar un equipo sin cliente existente | El sistema no permite guardar el equipo | Recepcionista | |
| CP06 | RF03 | Crear una orden con la falla reportada para un cliente y un equipo | La orden queda asociada a ambos | Recepcionista | |
| CP07 | RF03 | Generar el comprobante de la orden | El comprobante muestra número de orden y fecha | Recepcionista | |
| CP08 | RF04 | Asignar un técnico a una orden | La orden muestra el técnico asignado | Recepcionista | |
| CP09 | RF04 | Iniciar sesión como técnico | El técnico ve solo las órdenes que le corresponden | Técnico | |
| CP10 | RF05 | Cambiar el estado de una orden entre los cinco estados permitidos | El estado se actualiza correctamente | Técnico | |
| CP11 | RF05 | Revisar el registro de un cambio de estado | Queda guardado con fecha y usuario | Técnico | |
| CP12 | RF06 | Consultar el historial por cliente | Se muestran sus órdenes y cambios de estado | Administrador | |
| CP13 | RF06 | Consultar el historial por equipo | Se muestran las órdenes y cambios de ese equipo | Administrador | |
| CP14 | RF07 | Intentar acceder a una función sin iniciar sesión | El sistema niega el acceso | Sin sesión | |
| CP15 | RF07 | Probar con cada rol las funciones que no le corresponden | Cada rol solo ve las funciones permitidas | Los tres roles | |

## Resumen de ejecución

| Indicador | Meta | Valor obtenido |
| --- | --- | --- |
| K4. Requisitos funcionales aprobados | 7 de 7 | |
| K5. Órdenes de prueba con técnico asignado | 100 % | |
| K6. Errores críticos abiertos | 0 | |
