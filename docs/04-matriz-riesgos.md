# Matriz de riesgos y contingencias

Nivel de riesgo = probabilidad (P) x impacto (I). Clasificación: **bajo** de 1 a 6, **medio** de 7 a 12 y **alto** de 13 a 25.

| Valor | Probabilidad | Impacto |
| --- | --- | --- |
| 1 | Muy baja | Muy bajo |
| 2 | Baja | Bajo |
| 3 | Media | Medio |
| 4 | Alta | Alto |
| 5 | Muy alta | Muy alto |

## Matriz

| Cód. | Riesgo | P | I | Nivel | Mitigación | Contingencia | Responsable |
| --- | --- | --- | --- | --- | --- | --- | --- |
| R1 | Retraso por poca disponibilidad de tiempo de un integrante (exámenes, feriados y fin de año) | 4 | 4 | **16** (alto) | Planificar solo 10 h semanales por persona, repartir tareas y revisar el tablero dos veces por semana | Redistribuir tareas y mover al siguiente sprint las funciones de menor prioridad, como RF06 | Mariaelis |
| R2 | Poca experiencia del equipo con la tecnología elegida | 3 | 4 | **12** (medio) | Elegir en el Sprint 1 una tecnología conocida y hacer una prueba corta | Cambiar a una tecnología más simple y pedir orientación al docente | Julian |
| R3 | Cambios en los requisitos durante el proyecto | 3 | 3 | **9** (medio) | Revisar requisitos en el Sprint 1 y aplicar el control de cambios | Posponer el cambio al siguiente sprint y volver a priorizar el backlog | Jean |
| R4 | Pérdida de archivos o de código | 2 | 5 | **10** (medio) | Guardar el código en GitHub y los documentos en Drive, con commits frecuentes | Restaurar la última versión guardada en GitHub o Drive | Julian |
| R5 | Conflicto o ausencia de un integrante | 2 | 4 | **8** (medio) | Aplicar las reglas del equipo y mantener comunicación constante | Aplicar el escalamiento de tres pasos y redistribuir tareas | Mariaelis |
| R6 | Fallas de internet o de electricidad | 3 | 2 | **6** (bajo) | Trabajar con copia local y subir cambios con frecuencia | Trabajar sin conexión y sincronizar después | Julian |
| R7 | Subestimación de las horas necesarias | 3 | 3 | **9** (medio) | Revisar las horas con el equipo y reestimar al inicio de cada sprint | Reducir el alcance de las funciones de prioridad media y reasignar horas | Jean |

## Mapa de calor (probabilidad por impacto)

| P \ I | 1 | 2 | 3 | 4 | 5 |
| --- | --- | --- | --- | --- | --- |
| **5** | | | | | |
| **4** | | | | R1 (alto) | |
| **3** | | R6 | R3, R7 | R2 | |
| **2** | | | | R5 | R4 |
| **1** | | | | | |

R1 es el único riesgo de nivel alto y recibe seguimiento semanal.

*Fuente: Informe FixIt, Módulo III (Tablas 23 y 24, Figura 4).*
