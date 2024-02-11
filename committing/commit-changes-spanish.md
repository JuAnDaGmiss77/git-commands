# Cambios commit

Este comando se utiliza para registrar cambios en el repositorio.

**Usage:**

```bash
git commit -m "Commit message"
```

Este comando crea un nuevo commit que contiene los cambios preparados en el índice. Abre un editor de texto para ingresar un mensaje de commit si no se utiliza la bandera -m. El mensaje del commit debe describir brevemente los cambios realizados en el commit.

Para confirmar todos los cambios preparados, puedes usar:

```bash
git commit -a -m "Commit message"
```

Esto automáticamente preparará cualquier archivo modificado antes de confirmarlos.

Para enmendar el último commit, preservando su mensaje, puedes usar:

```bash
git commit --amend
```
Para enmendar el último commit y renombrar su mensaje, puedes usar:

```bash
git commit --amend "Rename commit message"
```