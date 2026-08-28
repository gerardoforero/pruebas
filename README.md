# Archivo de Prueba del Repositorio

Este archivo se utiliza únicamente para validar el flujo de trabajo de Git y GitHub.

## Objetivo

Verificar:

* Creación de archivos.
* Commit.
* Push a una rama de desarrollo.
* Creación de Pull Request.
* Revisión del Pull Request.
* Merge hacia la rama objetivo.
* Validación de trazabilidad en GitHub.

## Información de prueba

| Campo     | Valor                 |
| --------- | --------------------- |
| Tipo      | Archivo de prueba     |
| Propósito | Validación Git/GitHub |
| Ambiente  | Desarrollo            |
| Estado    | En prueba             |

## Cambios realizados

* Se creó el archivo `PRUEBA.md`.
* Se agregó documentación de prueba.
* Se utilizará para validar el flujo de ramas.

## Flujo Git esperado

```text
feature/prueba
      │
      │ Pull Request
      ▼
dev-pruebas
      │
      │ Pull Request
      ▼
dev
```

## Control

Este archivo no contiene código funcional del sistema.

Su propósito es validar que los cambios realizados en una rama puedan ser identificados, revisados y fusionados correctamente mediante Git/GitHub.

## Resultado esperado

El Pull Request debe mostrar:

1. La rama de origen correcta.
2. La rama destino correcta.
3. Únicamente los cambios esperados.
4. El commit asociado.
5. La revisión realizada.
6. El merge ejecutado por el mecanismo autorizado.

---

**Archivo creado para pruebas de control de versiones.**
