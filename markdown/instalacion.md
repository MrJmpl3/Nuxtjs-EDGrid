# Instalación

Puede usar EDgrid con [Sass](https://ed.team/cursos/sass) (recomendado) y [CSS](https://ed.team/cursos/css).

## Instalación de versión CSS

* Descargue la última versión de EDgrid desde [Github](https://github.com/escueladigital/EDgrid/archive/master.zip)
* Descomprima y busque la carpeta `src/css`. Dentro encontrará dos archivos: `ed-grid.css` y `ed-grid.min.css`. Incluya cualquiera de los dos a su proyecto y listo.
 * La unica diferencia entre estos archivos es que la versión `ed-grid.min.css` es minificada y la versión `ed-grid.css` incluye saltos de línea, indentación y comentarios si quiere estudiar como se construyó la librería.

## Instalación de versión Sass

Para instalar la versión Sass puede utilizar npm:

```bash
npm install --save-dev ed-grid
```

También puede usar yarn:

```bash
yarn add ed-grid --dev
```

Posteriormente, impórtelo en su estructura de archivos Sass

```scss
@import "~ed-grid/ed-grid"
```
