# Backoffice Taxi4fun

Modulo del front del proyecto https://github.com/taxy4fun en angular 4.4
El proyecto está preparado para desplegar en heroku mediante npm scripts (heroku-postbuild).
Tiene también dockerfile para generar las imágenes y desplegar. El docker arranca un express en el puerto indicado por variable de entorno env.PORT

### Branches CI

**master**


[![Build Status](https://travis-ci.org/taxy4fun/backoffice-y4f.svg?branch=master)](https://travis-ci.org/taxy4fun/backoffice-y4f)
[![Code Climate](https://codeclimate.com/github/taxy4fun/backoffice-y4f/badges/gpa.svg)](https://codeclimate.com/github/taxy4fun/backoffice-y4f)
[![Test Coverage](https://codeclimate.com/github/taxy4fun/backoffice-y4f/badges/coverage.svg)](https://codeclimate.com/github/taxy4fun/backoffice-y4f/coverage)
[![Dependencies](https://david-dm.org/taxy4fun/backoffice-y4f/repo.svg)](https://david-dm.org/taxy4fun/backoffice-y4f/)


**develop**

[![Build Status](https://travis-ci.org/taxy4fun/backoffice-y4f.svg?branch=develop)](https://travis-ci.org/taxy4fun/backoffice-y4f)

Despliegue de prueba en : https://backoffice-4yf-develop.herokuapp.com/


## Development server

`npm run api` para levantar el api mock con dyson
`ng serve` para arrancar servidor en `http://localhost:4200/`

## Build

`ng build` construir en `dist/`

## Running unit tests

`ng test`

## Running end-to-end tests

`ng e2e`


## Para desplegar en producción se ejecuta
El paso previo ejecuta `ng build --aot -prod` 
El despliegue ejecuta `node server.js` que arranca un node.
