# Guía del Laboratorio 02: Ramas, Merge y Resolución de Conflictos

Este proyecto corresponde al Laboratorio 02 del curso Diseño de Interfaces de Programación Avanzado. En este trabajo se practicó el uso de ramas en Git, la unión de cambios mediante merge, la resolución de conflictos y el uso de etiquetas para marcar una versión estable del proyecto.

## Objetivo del proyecto

El objetivo fue aprender a trabajar con ramas sin afectar directamente la rama principal, integrar cambios y resolver conflictos cuando dos ramas modifican la misma parte de un archivo.

### Herramientas utilizadas

- Git
- GitHub
- Visual Studio Code
- HTML
- CSS
## Pasos realizados

1. Crear el proyecto e inicializar el repositorio con Git.
2. Crear ramas para trabajar cambios de manera separada.
3. Realizar los cambios correspondientes en cada rama.
4. Fusionar las ramas con la rama principal mediante merge.
5. Resolver el conflicto generado entre las ramas color-azul y color-rojo.
6. Crear la etiqueta v1.0 para marcar una versión estable.
7. Publicar el proyecto en GitHub.

## Avance del proyecto

- [x] Crear las ramas del proyecto
- [x] Realizar los cambios y commits
- [x] Resolver el conflicto entre ramas
- [x] Fusionar los cambios con main
- [x] Publicar la versión en GitHub
## Archivos del proyecto

| Archivo | Descripción |
|---------|-------------|
| index.html | Contiene la estructura principal de la página web |
| estilos.css | Contiene los estilos y el color del título |
| .git | Guarda la información y el historial del repositorio Git |

## Comandos utilizados

Para comprobar las ramas del proyecto se utilizó el comando `git branch`.

También se utilizaron los siguientes comandos durante el desarrollo:

```bash
git checkout -b color-azul
git switch main
git merge color-azul
git merge color-rojo
git add estilos.css
git commit -m "Resuelve conflicto de color del titulo"
git tag -a v1.0 -m "Version estable del laboratorio 02"
```
## Enlace de referencia

Para conocer más sobre Git y sus comandos se puede consultar la [documentación oficial de Git](https://git-scm.com/doc).
## Captura del proyecto

![Imagen](../img/captura.jpg)