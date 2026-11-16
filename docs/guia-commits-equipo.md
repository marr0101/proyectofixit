# Guía de commits del equipo

Cada integrante debe hacer el trabajo y el commit desde su propia cuenta de GitHub. No se debe compartir la contraseña ni hacer commits en nombre de otra persona. Reemplacen `<URL_DEL_REPOSITORIO>` por el enlace HTTPS del repositorio.

## Pasos comunes

```bash
git clone <URL_DEL_REPOSITORIO>
cd FixIt
git checkout docs-planificacion
git pull origin docs-planificacion
```

Antes de confirmar el commit, verifica la identidad configurada en este repositorio:

```bash
git config user.name
git config user.email
```

Si no corresponde a tu cuenta, configúrala localmente para este repositorio:

```bash
git config user.name "Tu nombre"
git config user.email "Tu correo verificado de GitHub"
```

Después de crear o editar el archivo asignado, usa `git add`, `git commit` y `git push` con los comandos indicados en tu sección.

## Aporte: metodología y comunicación

Crear `docs/modulo-I-y-IV.md` con un resumen de la metodología elegida y el plan de comunicación, usando la información del informe. No agregues datos que no estén confirmados en el proyecto.

```bash
git add docs/modulo-I-y-IV.md
git commit -m "docs: agrega resumen de metodología y comunicación (Módulos I y IV)"
git push origin docs-planificacion
```

## Aporte: alcance y requisitos

Crear `docs/modulo-II.md` con el alcance del proyecto y la lista de requisitos funcionales RF01 a RF07, transcritos o resumidos fielmente del informe. No inventes el contenido de los requisitos.

```bash
git add docs/modulo-II.md
git commit -m "docs: agrega alcance y requisitos funcionales (Módulo II)"
git push origin docs-planificacion
```

## Aporte: riesgos y herramientas

Crear `docs/modulo-III-y-V.md` con un resumen del plan de riesgos y de las herramientas usadas, basado en el informe y en la información confirmada del proyecto.

```bash
git add docs/modulo-III-y-V.md
git commit -m "docs: agrega resumen de riesgos y herramientas (Módulos III y V)"
git push origin docs-planificacion
```
