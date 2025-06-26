# Artículo Básico sobre Git

Este artículo está diseñado para principiantes que desean aprender los fundamentos de Git, un sistema de control de versiones distribuido ampliamente utilizado en desarrollo de software. Aquí encontrarás explicaciones paso a paso de comandos clave y conceptos para que comiences a gestionar tu código de forma efectiva.

## Tabla de Contenidos
- [Artículo Básico sobre Git](#artículo-básico-sobre-git)
  - [Tabla de Contenidos](#tabla-de-contenidos)
  - [Introducción](#introducción)
  - [Cómo Empezar](#cómo-empezar)
    - [Requisitos Previos](#requisitos-previos)
    - [Instalación](#instalación)
  - [Comandos Básicos de Git](#comandos-básicos-de-git)
    - [Inicializar un Repositorio](#inicializar-un-repositorio)
    - [Hacer un Commit](#hacer-un-commit)
  - [Contribuyendo](#contribuyendo)
  - [Licencia](#licencia)

## Introducción
Este artículo está diseñado para principiantes que desean aprender los fundamentos de Git, un sistema de control de versiones distribuido ampliamente utilizado en desarrollo de software. Aquí encontrarás explicaciones paso a paso de comandos clave y conceptos para que comiences a gestionar tu código de forma efectiva.

## Cómo Empezar
Para seguir este artículo, asegúrate de tener Git instalado en tu computadora. Puedes descargarlo desde [git-scm.com](https://git-scm.com/).

### Requisitos Previos
- Una terminal o interfaz de línea de comandos
- Conocimiento básico de sistemas de archivos

### Instalación
1. Descarga e instala Git desde [la página oficial](https://git-scm.com/downloads).
2. Verifica la instalación ejecutando `git --version` en tu terminal.

## Comandos Básicos de Git
### Inicializar un Repositorio
Para comenzar un nuevo repositorio de Git, navega a tu carpeta de proyecto y ejecuta:
```bash
git init
```
Esto crea un directorio `.git` para rastrear tu proyecto.

### Hacer un Commit
Después de realizar cambios, agrégalos y haz un commit con:
```bash
git add .
git commit -m "Commit inicial"
```
La bandera `-m` agrega un mensaje que describe tus cambios.

## Contribuyendo
¡Las contribuciones son bienvenidas! Por favor, sigue estos pasos:
1. Haz un fork de este repositorio.
2. Crea una nueva rama: `git checkout -b nombre-de-funcion`.
3. Realiza tus cambios y comítelos: `git commit -m "Añadir nueva función"`.
4. Sube la rama: `git push origin nombre-de-funcion`.
5. Envía un pull request.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.