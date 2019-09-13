# TourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.8.

[Official Tutorial](https://angular.io/tutorial).

## Notes
- `ng new name-of-project`: To create a new project
- `ng generate component new-component`: To create a new **Component**. Prefer to use Angular Cli, besides the time gained it already configure the app module to make the component work.
- `ng generate service service-name`: To create a new **Service**. Todo, find a way to create the services on an specific folder.
- Angular Services works with **Dependency Injection** auto-wire. We declare where it's available on `providedIn` at `@Injectable`, and so on we can pass the class on constructors and Angular will wire it for us.
- A Service **must** be public at a component ts class, if it's going to be binded (see `messages component`)


## Project

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
