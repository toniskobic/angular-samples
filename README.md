# Angular Samples

Angular 15 application with a responsive UI containing multiple samples demonstrating various Angular features.

This application demonstrates the implementation and use of:
- Template Driven Forms
- Reactive Forms
- Validators (both sync and async)
- Directives
- Pipes
- Services
- @ViewChild decorator
- ng-template, ng-container and ngTemplateOutlet
- Sending requests to a REST API

REST API is mocked using [json-server](https://github.com/typicode/json-server).

Proxy is configured for making API calls to a mocked REST API.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.1.

## Development server

To run a dev server with proxy set up 
```
npm run start-proxy
```
and mocked REST API
```
npm run api
```
Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
