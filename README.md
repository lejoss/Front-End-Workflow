# Front-End-Workflow

Front End Conventions

Proceso mediante el cual se implentara el desarrollo de software Front End  utilizando las siguientes tecnologias:
- HTML5
- CSS3
- JAVASCRIPT


### Workflow Front End

Tecnologias usadas:
  - Yeoman
  - AngularJS
  - Bootstrap
  - SASS / SMACSS
  - GULP
  - NODEJS ( npm )
  - BOWER
  - GIT


### convenciones para la codificacion con AngularJs

Actualmente nos basamos en esta guia de [John Papa] de la cual usamos los siguientes puntos.

- Single Responsibility
- IIFE
- Modules
- Controllers
- Services
- Factories
- Data Services
- Promises

### convenciones para nombrar los archivos

Patron para nombrar archivos "caracteristica.tipo.js"

Ejemplos
 - Nombre del Archivo : ( radicacion.controller.js | radicacion.factory.js )
 - Llamar los componentes registrados : ( RadicacionController )


### UI-Router
Enrutador de la aplicacion
ver:
 - State
 - ui-sref
 - States anidados

leer mas [ui-router]


### Restangular
Restangular sera el servicio que atendera todas las llamadas HTTP

[Restangular Github]

[Restangular Newsletter]

###  Promesas

Angular Docs:  [Angular $q]

Manejo de Promsesas js: [Promises]

### JSON API Estatica

En este caso crearemos un directorio API en el cual tendremos los modelo de datos estaticos [Archivos JSON], Estos JSON serviran de Endpoint para nuestros contradores restangularizados.

### Unit Test Karma y Jasmine

**Karma** : Test Runner

**Jasmine** : Behavior-Driven JavaScript

#####instalacion

**paso 1:** Instalar Karma CLI

<code> npm install -g karma-cli </code>

**paso 2:**  Instalar karma localmente en la carpeta de "**tests**"

<code>npm install karma</code>

**paso 3:** Instalar Karma Plugins

<code> npm install karma-jasmine karma-phantomjs-launcher</code>

**paso 4:** Ejecutar el archivo karma.conf.js

<code>karma start</code>


##### Angular Mocks
Se usara "Angular Mocks" para las pruebas unitarias sobre controladores ... [Leer mas]
##### Ejemplo probar peticion Http en  controlador con karma-jasmine + ngMocks
[$httpBackend]

##### Filtros en Angular
[Todo sobre Filtros AngularJs]

[$http angular]:https://docs.angularjs.org/api/ng/service/$http
[John Papa]:https://github.com/johnpapa/angular-styleguide
[Leer mas]:https://docs.angularjs.org/guide/unit-testing
[Todo sobre Filtros AngularJs]:http://toddmotto.com/everything-about-custom-filters-in-angular-js/
[Restangular Github]:https://github.com/mgonto/restangular
[Restangular Newsletter]: http://www.ng-newsletter.com/posts/restangular.html
[$httpBackend]:https://code.angularjs.org/1.3.15/docs/api/ngMock/service/$httpBackend
[Promises]:http://pouchdb.com/2015/05/18/we-have-a-problem-with-promises.html
[Angular $q]:https://docs.angularjs.org/api/ng/service/$q
[ui-router]: https://github.com/angular-ui/ui-router
