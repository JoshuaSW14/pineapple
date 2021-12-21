# Pineapple

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Adding Component

Run `ng generate component components/component-name`. This generates a new component under the components folder

Define `<app-component-name></app-component-name>`. Use this where you want your component to be displayed

Then you can edit the HTML and TS file of that component to display what you want.

## Adding Shared Component

Run `ng generate component shared/component-name`. This generates a new component under the shared folder

Add the import, declaration, and export to the shared.module.ts file. That looks like this:

Import - `import { component-nameComponent } from './component-name/component-name.component';`

Declaration - `component-nameComponent`

Exports - `component-nameComponent`

Define `<app-component-name></app-component-name>`. Use this where you want your component to be displayed

Then you can edit the HTML and TS file of that component to display what you want.
