# Guía de contribución

## Planificación
Organiza las Issues en Milestones y Projects. Asigna responsable y etiqueta. Actualiza el estado Todo, In Progress o Done según el progreso real.

## Flujo de trabajo
1. Seleccionar una Issue asignada.
2. Actualizar main (`git switch main`, `git pull origin main`).
3. Crear una rama de trabajo y realizar cambios.
4. Registrar commits y publicar la rama.
5. Abrir una Pull Request hacia main y vincular la Issue.
6. Solicitar revisión, corregir observaciones y resolver conflictos.
7. Integrar tras la aprobación y actualizar main local.
8. Publicar tag y Release cuando se complete la versión.

## Protección de main
No desarrollar directamente sobre main. Configurar reglas de protección cuando estén disponibles. No fusionar sin revisión de otro integrante.

## Code Review
Revisar los archivos modificados, comprobar requisitos y pruebas, dejar comentarios técnicos y solicitar correcciones si procede.

## Conflictos
Actualizar la rama, identificar los cambios incompatibles, acordar la solución con el compañero, comprobar el resultado y registrar la resolución.

## Versionado
Milestones: vX.Y. Tags y Releases: vX.Y.Z (mayor, menor, parche). Publicar desde un commit estable de main.

## Archivos ignorados
Mantener .gitignore en la raíz. No versionar secretos, cachés ni entornos virtuales. Recordar que .gitignore no deja de seguir archivos ya versionados.

## Calidad del código
Comprobar funcionamiento, legibilidad, pruebas y documentación antes de integrar.

## Configuración inicial
Crear las etiquetas enhancement, bug, documentation, refactor y test si no existen. Publicar las plantillas en la rama predeterminada. Las plantillas de Issues y PR se reconocen automáticamente; las de templates/ se utilizan manualmente. Esta guía no aplica por sí sola restricciones técnicas.
