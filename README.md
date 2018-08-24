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
## El proyecto

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

### Las carpetas donde se encuentran la información de los componentes son:

- [Assets](#assets)

- [Components](#components)

- [SCSS](#scss)

- [Router](#router)

## Assets

En esta carpeta se alojan las imágenes que se usan en el proyecto

## Components

Esta carpeta se divide en 2 partes **Routes** y **UI**

### Routes

Aquí se encuentra cada una de las vistas del proyecto. Ej:

```bash
Login.vue
```

Para la creción de nuevos archivos de vistas se debe usar la nomenclatura *PascalCase* con extensión de archivo *.vue*

### UI

En esta carpeta se encuentran los archivo de los componentes que se integran en cada vista
