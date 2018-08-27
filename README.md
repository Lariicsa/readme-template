# readme-template
a few readme templates

# Administrador Genércio ASC

Aplicación cliente para el sistema de gestión administrativo de ASC.

Después de la clonación del proyecto

**Correr en BASH**  ( *debes tener instalado [NPM](https://www.npmjs.com/) y [Node](https://nodejs.org)* )

``` bash
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev

# compilar para producción
npm run build
```
#y El proyecto

``` 
    .
    .
    ├── src/
        ├── api
        ├── assets
        ├── components
        ├── config
        ├── router
        ├── scss
        ├── helpers
        ├── mediator
        ├── services
        ├── store
        .
        .
```

Las carpetas donde se encuentran la información de los componentes son:

- [Assets](#Assets)

- [Components](#Components)

- [SCSS](#SCSS)

- [Routes](#Routes)

## Assets 📁

En esta carpeta se alojan las imágenes que se usan en el proyecto

## Components 📁

Esta carpeta se divide en 2 partes **Routes** y **UI**

### Routes 📁

En esta carpeta se encuentra cada una de las vistas del proyecto. Ej: `bash Login.vue 📄`

Para la creción de nuevos archivos de vistas se debe usar la nomenclatura *PascalCase* con extensión de archivo *.vue*

**UI-TESTS**

Es un archivo que se encuentra dentro de `Routes` tiene contenidos la muestra de los componentes existentes, también, se pueden hacer pruebas dentro de este archivo.

### UI 📁

En esta carpeta se encuentran los archivos de los componentes que se integran en cada vista. Los componentes que pueden llegar a confundirse con elementos nativos, llevan el prefijo `asc-` + `nombre-del-componente`,
Los componentes existentes son los siguientes:

* Alert
* Button
* Checkbox
* DropDown
* Footer
* Header
* InputField
* InnerTable
* Label
* Paginator
* RadioButton
* Spinner
* Switch
* Table
* Tag
* ToggleButton

## SCSS 📁

En esta carpeta se encuentran los archivos de los estilos globales que comparten los componentes o el ambiente general (*layout*). Los cuales son:
```
├── scss/
        ├── _vars.scss
        ├── global.scss
        ├── normalize.scss
 ```
 
   ### _vars📄
 
 En este archivo se encuentran las variables del lauyout general y de los componentes. Por ej:
  ```scss
$mint: #eef9f8;
$mustard: #f5a623;
$snow: #ffffff;

```
Cualquier modificación general que se desee hacer, se debe agregar en este archivo

   ### global.scss📄
 
 En este archivo se encuentran las reglas generales del layout y reglas que comparten algunos componentes. Por ej:
  ```scss
.space {
	background-color: $snow;
	display: flex;
	flex-direction: column;
	flex-wrap: wrap;
	justify-content: flex-start;
	width: 100%;
	height: 100%;
}
```
Cualquier modificación general que se desee hacer, se debe agregar en este archivo.

### normalize.scss📄

Este archivo es el *reset* de los elementos web.
[normalize.css v7.0.0 ](http://github.com/necolas/normalize.css)
 
