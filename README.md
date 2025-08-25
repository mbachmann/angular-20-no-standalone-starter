# Angular 20 Starter No Standalone (contains @NgModule)

https://github.com/mbachmann/angular-20-no-standalone-starter

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.2.0.

The starter project contains the following libraries and settings:

- refactor to the existing naming with `suffixes`
- schematics contains the changes for the existing naming with suffixes
- schematics contains `eslint/schematics`
- prettier library with `.prettierrc.json` and `.prettierignore`
- eslint library with `prettier-eslint`, `eslint-config-prettier` and `eslint-plugin-prettier`
- `package.json` contains scripts for prettier and eslint
- Karma Configuration
- Fortawsome and Bootstrap Library


## Linting and Prettier

```bash
npm run prettier:check
npm run prettier:write


npm run lint:check
npm run lint:fix
```


## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

Unit Tests can be executed (run or debug) with Karma. Create in your IDE a run configuration. 


## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
