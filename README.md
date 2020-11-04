# MatSelect Autocomplete component for Angular Material

### Forked from: Crono fork
Combination of drog (angular/material 8 update) and oak's forks of mat-select-autocomplete + 1 fix

### Forked from:

[https://github.com/drog/mat-select-autocomplete](https://github.com/drog/mat-select-autocomplete)

#### Changes

[1.4.5]
- Make search bar sticky

[1.4.2]
- Add fix to check if selectedValue is null to prevent some not a property of null errors
- Bumped package version to 1.4.2

#### Installation

`npm install crono-mat-select-autocomplete --save`

---

_Oak's readme:_

### Forked from:

[https://github.com/malothnaresh/mat-select-autocomplete](https://github.com/malothnaresh/mat-select-autocomplete)

#### Changes

- add optional input for using `<mat-label>`
- update peer dependencies to 6.1.10
- fix [(ngModel)] deprecation warning
- bumped package version to 1.3.1

#### Installation

`npm install oak-mat-select-autocomplete --save`

#### Demo

https://stackblitz.com/edit/mat-select-autocomplete

#### Documentation

https://medium.com/@cryptoipl/angular-material-multi-select-with-autocomplete-113065d58dab

---

_Original readme:_

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.4.

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

## Demo

https://stackblitz.com/edit/mat-select-autocomplete

## Documentation

https://medium.com/@cryptoipl/angular-material-multi-select-with-autocomplete-113065d58dab

## To build package

npm run package

## To publish the package

npm login
npm publish ./dist/select-autocomplete/mat-select-autocomplete-1.2.1.tgz
