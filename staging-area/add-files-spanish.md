# Agregar Archivos al Área de Preparación

Este comando se utiliza para agregar archivos al área de preparación en preparación para un commit.

```bash
git add <file1> <file2> ...
```

Este comando coloca los archivos especificados en el área de preparación para el próximo commit. Los agrega al área de preparación, también conocida como el índice, donde se marcan los cambios para incluirlos en el próximo commit.

Para agregar todos los archivos modificados y nuevos al área de preparación, puedes usar:


```bash
git add .
```
Para agregar todos los cambios, incluyendo eliminaciones, puedes usar:

```bash
git add -A
```