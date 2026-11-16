# Cronograma, hitos y diagrama de Gantt

Inicio: lunes 30 de noviembre de 2026. Cierre: viernes 22 de enero de 2027 (supuesto del equipo).
Feriados considerados: 8 de diciembre, 25 de diciembre y 1 de enero.

```mermaid
gantt
    title FixIt - 8 semanas, 4 sprints
    dateFormat YYYY-MM-DD
    axisFormat %d/%m

    section Transversal
    1.2 Seguimiento y reuniones - Julian        :2026-11-30, 2027-01-22
    1.3 Gestión de riesgos y cambios - Julian   :2026-11-30, 2027-01-22

    section Sprint 1
    1.1 Planificación y acta - Jean              :2026-11-30, 2026-12-11
    2.1 Requisitos - Jean                        :2026-11-30, 2026-12-11
    2.2 Modelo de datos - Julian                 :2026-11-30, 2026-12-11
    2.3 Diseño de interfaces - Mariaelis         :2026-11-30, 2026-12-11
    H1 Requisitos y diseño aprobados             :milestone, 2026-12-11, 0d

    section Sprint 2
    3.1 Base de datos y RF07 - Julian            :2026-12-14, 2026-12-24
    3.2 RF01 Clientes - Mariaelis                :2026-12-14, 2026-12-24
    3.3 RF02 Equipos - Jean                      :2026-12-14, 2026-12-24
    3.4 RF03 Órdenes de servicio - Julian        :2026-12-14, 2026-12-24
    H2 Clientes, equipos y órdenes               :milestone, 2026-12-24, 0d

    section Sprint 3
    3.5 RF04 Asignación de técnicos - Jean       :2026-12-28, 2027-01-08
    3.6 RF05 Control de estados - Jean            :2026-12-28, 2027-01-08
    3.7 RF06 Historial - Mariaelis               :2026-12-28, 2027-01-08
    4.1 Plan de pruebas - Mariaelis              :2026-12-28, 2027-01-08
    H3 Asignación, estados e historial           :milestone, 2027-01-08, 0d

    section Sprint 4
    4.2 Pruebas funcionales - Los tres           :2027-01-11, 2027-01-22
    4.3 Corrección de errores - Los tres         :2027-01-11, 2027-01-22
    5.1 Manual de usuario - Mariaelis            :2027-01-11, 2027-01-22
    5.2 Entrega y capacitación - Jean            :2027-01-11, 2027-01-22
    1.4 Cierre y lecciones aprendidas - Mariaelis :2027-01-11, 2027-01-22
    H4 Cierre del proyecto                       :milestone, 2027-01-22, 0d
```

## Sprints (capacidad: 60 h por sprint)

| Sprint | Fechas | Objetivo | Tareas de la EDT | Horas |
| --- | --- | --- | --- | --- |
| 1 | 30 nov al 11 dic | Planificar, definir requisitos y diseñar | 1.1, 2.1, 2.2, 2.3 | 53 + 7 |
| 2 | 14 al 24 dic | Base del sistema y registro de clientes, equipos y órdenes | 3.1, 3.2, 3.3, 3.4 | 53 + 7 |
| 3 | 28 dic al 8 ene | Asignación, estados e historial, y plan de pruebas | 3.5, 3.6, 3.7, 4.1 | 53 + 7 |
| 4 | 11 al 22 ene | Pruebas, correcciones, manual y cierre | 4.2, 4.3, 5.1, 5.2, 1.4 | 53 + 7 |

## Hitos

| Hito | Descripción | Fecha prevista |
| --- | --- | --- |
| H1 | Requisitos, modelo de datos y prototipos aprobados (E1 a E3) | Viernes 11 de diciembre de 2026 |
| H2 | Módulos de clientes, equipos y órdenes entregados (E4 a E6) | Jueves 24 de diciembre de 2026 |
| H3 | Asignación de técnicos, estados e historial entregados (E7 a E9) y plan de pruebas listo | Viernes 8 de enero de 2027 |
| H4 | Pruebas, correcciones, manual de usuario y cierre completados (E10 a E12) | Viernes 22 de enero de 2027 |

*Fuente: Informe FixIt, Módulo II (Tablas 17 y 18, Figura 3).*
