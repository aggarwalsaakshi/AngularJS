# AngularJS 6

Every angular application has atleast one module called root module also called app module
Each module is in turn made up of component and services
Component 
component controls a portion of the view on the browser
Angular app has atleast one component called root or app component
All other components are nested inside this component
Each component will have an html template  to represent the view in the browser and a class to control the logic of that view
module will have services basically a class which conatin business logic

modele contain componen and service
package.json contain the dependencies

npm start internally called ng serve command

In src folder ther is one main.ts file which is the entry point of our application
app.module.ts which is root module of our application
app.component.ts  which is root component of our application

when run command ng serve the execution comes to the main.ts we bootstrap or kick start the app module, in app module we bootstart the app 
component  and this component  have html and  class to contain the logic and data to control the view 

# Hello

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
Angular-cli
 command line interface for angular-6
 allow you to generate building bock of your angular app by just type some command