# WebGraphic-style-webpack
Este repo tiene como finalidad ver como puede webpack resolver el tema de crear css centralizados o js centralziados para crear un propio repositorio base. 
De esta forma, sólo se incluye esos componentes que pueden ser únicos y utilizados sólo en una página sin interver el core de la imterfaz gráfica y de los Js que son usados de forma transversal.

### para ejecutar el proyecto sólo deben hacer los pasos siguientes:

Previamente deben ingresar a una terminal DOS o Powershell, hasta llegar al directorio del proyecto, que deben contener el package.json, es ahí el root del projecto.
Una ves ahí deben inicar con las sigueintes instrucciones de NPM.

1. "npm init -y",
    "npm install webpack --save-dev",
    "npm install webpack-cli --save-dev" 
    
2. npm run build - esta instrucción estará constantemente ejecutandose en segundo plano para compilar la salida de archivos 
dentro del directorio "dist".

*. De no ejecutarse de forma correcta y entrega errores de módulo, deben inicar con el punto "mini-css-extract-plugin".

## Webpack
Webpack is used to compile JavaScript modules. Once installed, you can interface with webpack either from its CLI or API. If you're still new to webpack, please read through the core concepts and this comparison to learn why you might use it over the other tools that are out in the community.
https://webpack.js.org/guides/getting-started/

## Getting started - Bootstrap (currently v3.3.7)
Bootstrap (currently v3.3.7) has a few easy ways to quickly get started, each one appealing to a different skill level and use case. Read through to see what suits your particular needs.
https://getbootstrap.com/docs/3.3/getting-started/#examples

### bootstrap Release 3.3.7 by NPM
instrucción NPM para instalar bootstrap "npm install bootstrap@3.3.7" -
https://libraries.io/npm/bootstrap/3.3.7

## Why generate a new package.json?
This plugin is useful for when you have a large source project for development / testing from which smaller Node.js projects are bundled for various deployments and applications. Such as Google Cloud Functions.
https://www.npmjs.com/package/generate-package-json-webpack-plugin

## mini-css-extract-plugin
This plugin extracts CSS into separate files. It creates a CSS file per JS file which contains CSS. It supports On-Demand-Loading of CSS and SourceMaps.
https://www.npmjs.com/package/mini-css-extract-plugin

## PostCSS Loader
Loader for webpack to process CSS with PostCSS
https://www.npmjs.com/package/postcss-loader

## Sass Loader
Loads a Sass/SCSS file and compiles it to CSS.
https://www.npmjs.com/package/sass-loader

## autoprefixer
PostCSS plugin to parse CSS and add vendor prefixes to CSS rules using values from Can I Use. It is recommended by Google and used in Twitter and Alibaba.
https://www.npmjs.com/package/autoprefixer#webpack

## Loading Fonts with webpack
In this tutorial, I'll show you how to get fonts working with webpack and explain the fine details along the way to better your understanding of webpack as a whole. We're going to start with a basic webpack config that compiles SCSS down to CSS. Download the repo, install its dependencies (use yarn or npm install), and let's get started.
https://chriscourses.com/blog/loading-fonts-webpack


