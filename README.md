# LocalWebsite

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Added Modules

First commit -- > primeng and primengicons

## Add bootstrap 4 module
npm install --save bootstrap
    @import "~bootstrap/dist/css/bootstrap.css" in style.scss

Adding Bootstrap 4 Using ng-bootstrap and ngx-bootstrap
    npm install --save @ng-bootstrap/ng-bootstrap
import the main module -- > import {NgbModule} from '@ng-bootstrap/ng-bootstrap';
Add the module imported in the app root module --> 
    import {NgbModule} from '@ng-bootstrap/ng-bootstrap';
Add it in the styles array of the angular.json
    "styles": [
        "styles.css",
        "node_modules/bootstrap/dist/css/bootstrap.css"
    ],

## Add fontawesome module 
npm install --save font-awesome angular-font-awesome
Import the module
    import { AngularFontAwesomeModule } from 'angular-font-awesome';
Add the font-awesome CSS to styles inside the angular.json
    "node_modules/font-awesome/css/font-awesome.css"
