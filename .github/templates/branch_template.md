# Convención de ramas
Documento de referencia manual.

## Formato
`tipo/numero-issue-descripcion`

Usa minúsculas, guiones, sin espacios ni tildes. Crea la rama desde main actualizada. Publica la rama y abre una PR. Elimina la rama cuando esté integrada y ya no sea necesaria.

En local se borrará después de:
git branch -d nombre-de-la-rama

En remoto se borrará despues de:
git push origin --delete nombre-de-la-rama

Además para borrar cualquier referencia de la rama en todo el repositorio:
git fetch --prune

## Tipos y ejemplos
| Prefijo | Finalidad | Ejemplo |
|---|---|---|
| `feature/` | Nueva funcionalidad | `feature/12-anadir-cambio` |
| `fix/` | Corrección de errores | `fix/12-corregir-cambio` |
| `docs/` | Documentación | `docs/12-actualizar-cambio` |
| `test/` | Pruebas | `test/12-comprobar-cambio` |
