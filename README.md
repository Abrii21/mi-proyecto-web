
# Mi Proyecto Web

## Descripción

Este proyecto consiste en el desarrollo de un sitio web utilizando HTML.

El objetivo principal es poner en práctica los conocimientos
adquiridos sobre Git, GitHub, control de versiones, creación
de ramas, commits, Pull Requests y documentación mediante Markdown.

## Tabla de contenidos

- [Instalación](#instalación)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Mejoras implementadas](#mejoras-implementadas)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Control de versiones](#control-de-versiones)

## Instalación

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/Abrii21/mi-proyecto-web.git
   ```

2. Acceder a la carpeta:

   ```bash
   cd mi-proyecto-web
   ```

3. Abrir el archivo `index.html` en un navegador web.

## Estructura del proyecto

```text
mi-proyecto-web/
│
├── index.html
├── .gitignore
└── README.md
```

## Mejoras implementadas

### 1. Menú de navegación

Se ha incorporado un menú de navegación utilizando
las etiquetas `<nav>`, `<ul>`, `<li>` y `<a>`.

Permite desplazarse entre las secciones de la página:
- Inicio.
- Sobre el proyecto.
- Contacto.

Rama utilizada: `feature/menu`.

### 2. Formulario de contacto

Se ha añadido un formulario utilizando etiquetas HTML
para recoger los siguientes datos:
- Nombre.
- Correo electrónico.
- Asunto.
- Mensaje.

Se han incorporado campos obligatorios mediante
el atributo `required`.

Rama utilizada: `feature/formulario-contacto`.

## Tecnologías utilizadas

- HTML5.
- Git.
- GitHub.
- Markdown.

## Control de versiones

El proyecto utiliza Git para gestionar los cambios
y GitHub para alojar el repositorio remoto.

Las mejoras se han desarrollado en ramas independientes
y se han incorporado a la rama principal `master`
mediante Pull Requests.
