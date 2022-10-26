#![Code-Igniter](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
This is a quick example of how to setup form validation in Angular 10 using Reactive Forms. The example is a simple registration form with pretty standard fields for title, first name, last name, date of birth, email, password, confirm password and an accept terms and conditions checkbox. All fields are required including the checkbox, the dob must be a valid date, the password field must have a min length of 6 and the email address must be in a valid format. There's also a custom MustMatch validator which is used to validate that the confirm password and password fields match.

I've setup the form to validate on submit rather than as soon as each field is changed, this is implemented with a submitted property in the app component that is set to true when the form is submitted for the first time, and reset to false if the cancel button is clicked.


# MyApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.1.0.

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
