# NGAPP

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.0.

## SCRIPTS

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## UX/UI 

### Angular Material

The project includes angular material core.

### Bootstrap customization

The project includes only the Bootstrap utilities that we need to development. If you prefer, it is able to remove the bootstrap @import on ITCSS arquitecture and to consume the *'/node_modules/bootstrap/dist/css/bootstrap.min.css'* file in the angular.json file if you need to. To do this, look at for **'arquitec'** definition, in *'build>options'* section include the call before styles.css file invocation.

### ITCSS arquitecture

The project includes a scss folder with all files. The styles.scss file includes all the @imports needed and it is prepared to add new features and components.
