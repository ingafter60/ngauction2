# NgAuction

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.1.

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

<<<<<<< HEAD
## 2.7.1. The initial project setup for ngAuction
=======
## 2.7.1. The initial project setup for ngAuction 
>>>>>>> 3e779d90d001c43f77f63180c8eabaf13693f481

ng new ngAuction --prefix nga --routing

ng serve -o

npm i bootstrap jquery popper.js --save-prod

<<<<<<< HEAD
"styles": [ "styles.css", "../node_modules/bootstrap/dist/css/bootstrap.min.css" ]

"scripts": [ "..node_modules/jquery/dist/jquery.min.js", "..node_modules/bootstrap/dist/js/bootstrap.min.js" ]

## 2.7.2. Generating components for ngAuction 

Listing 2.16. Generating components for ngAuction 

ng g c home

ng g c carousel

ng g c footer

ng g c navbar

ng g c product-item

ng g c product-detail

ng g c search

ng g c stars

ng g s shared/product

@NgModule({
  ...
  providers: [ProductService],
  ...
})

export class AppModule { }
=======
"styles": [
  "styles.css",
  "../node_modules/bootstrap/dist/css/bootstrap.min.css"
]

"scripts": [
  "..node_modules/jquery/dist/jquery.min.js",
  "..node_modules/bootstrap/dist/js/bootstrap.min.js"
]
>>>>>>> 3e779d90d001c43f77f63180c8eabaf13693f481
