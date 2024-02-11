# Fusionar Ramas

Este comando se utiliza para integrar cambios de una rama en otra.

**Usage:**

```bash
git merge <branch-name>
```

Este comando fusiona la rama especificada en la rama actual. Combina los cambios realizados en la rama especificada con los cambios en la rama actual. Si no hay conflictos, Git realizará automáticamente la fusión. Si hay conflictos, puede ser necesaria una intervención manual para resolverlos.

Para fusionar una rama en la rama actual y crear automáticamente un commit de fusión, puedes usar:

```bash
git merge --no-ff <branch-name>
```

Esto evitará que Git realice una fusión de avance rápido y creará un nuevo commit de fusión, incluso si la fusión podría resolverse automáticamente.

Si deseas abortar el proceso de fusión y volver al estado antes de que comenzara la fusión, puedes usar:

```bash
git merge --abort
```
Esto deshará la fusión y dejará la rama en su estado anterior a la fusión.