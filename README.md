# MeanApp
Angular 4 + ExpressJS.
[MEAN App tutorial](https://scotch.io/tutorials/mean-app-with-angular-2-and-the-angular-cli)

## 1. Setup
```bash
$ ng new mean-app
  create mean-app/README.md (1098 bytes)
  create mean-app/.angular-cli.json (1126 bytes)
  create mean-app/.editorconfig (245 bytes)
  create mean-app/.gitignore (516 bytes)
  create mean-app/src/assets/.gitkeep (0 bytes)
  create mean-app/src/environments/environment.prod.ts (51 bytes)
  create mean-app/src/environments/environment.ts (387 bytes)


  1 # MeanApp
  create mean-app/src/favicon.ico (5430 bytes)
  create mean-app/src/index.html (294 bytes)
  create mean-app/src/main.ts (370 bytes)
  create mean-app/src/polyfills.ts (2480 bytes)
  create mean-app/src/styles.css (80 bytes)
  create mean-app/src/test.ts (1085 bytes)
  create mean-app/src/tsconfig.app.json (211 bytes)
  create mean-app/src/tsconfig.spec.json (304 bytes)
  create mean-app/src/typings.d.ts (104 bytes)
  create mean-app/e2e/app.e2e-spec.ts (290 bytes)
  create mean-app/e2e/app.po.ts (208 bytes)
  create mean-app/e2e/tsconfig.e2e.json (235 bytes)
  create mean-app/karma.conf.js (923 bytes)
  create mean-app/package.json (1313 bytes)
  create mean-app/protractor.conf.js (722 bytes)
  create mean-app/tsconfig.json (363 bytes)
  create mean-app/tslint.json (3040 bytes)
  create mean-app/src/app/app.module.ts (314 bytes)
  create mean-app/src/app/app.component.css (0 bytes)
  create mean-app/src/app/app.component.html (1075 bytes)
  create mean-app/src/app/app.component.spec.ts (986 bytes)
  create mean-app/src/app/app.component.ts (207 bytes)
Installing packages for tooling via npm.
Installed packages for tooling via npm.
Project 'mean-app' successfully created.
```

## 2. Angular command line.
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.2.

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## 3. Add ExpressJS.

### Add expressjs and body-parser
```bash
$ npm install --save express body-parser
```

### Add `server.js` and `api.js`. Then build:
```bash
$ vi server.js
$ mkdir server
$ mkdir server/routes
$ vi server/routes/api.js

$ ng build
$ node server.js
```
Open Angular app at [http://localhost:3000](http://localhost:3000) and api at [http://localhost:3000/api](http://localhost:3000/api).
