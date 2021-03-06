# Configuración Básica de Webpack para React
  Webpack, Webpack-dev-Server, React, Babel, Sass.

![Screenshot](code.png) 

## Este Webpack workflow permite
- Uso de javascript ES6 con Babel.
- Uso de React y JSX ES6 con Babel (.js/.jsx)
- Carga y compilar HTML y minificarlo
- Carga y compilar SCSS a CSS y minificarlo
- Carga tipografias /fonts woff, woff2, ttf & eot
- Carga imagenes Gif, jpg y png y minifica el peso
- Carga archivos SVG

## Requerimientos

- NodeJs > v10.x;
- NPM > v6.4 ó yarn > v1.x

## Como usarlo?:

1. Clonar el Proyecto
2. Use ``cd webpack-workflow``
3. ``npm/yarn install``
4. ``npm/yarn start``

## Consideraciones
- La entrada de tus archivos está dentro de la carpeta: `src`
- El archivo webpack.config.js es para configurar webpack.

## Instalar dependencias de node.js
- Instalar dependencias de node.js: `npm/yarn install`

## Scripts creados para dev
- Borra y crea el proyecto en produccion:
  - Se inicia con:  `npx run build'` ó `yarn build`

- Iniciar un servidor local para desarrollo:
  - Se inicia con: `npm start` ó `yarn start`

## Contributing
Las solicitudes de modificaciones son bienvenidas. Para cambios importantes, abra primero una discusión para discutir qué le gustaría cambiar.

Asegúrese de actualizar las pruebas según corresponda.

## License
[MIT](https://choosealicense.com/licenses/mit/)