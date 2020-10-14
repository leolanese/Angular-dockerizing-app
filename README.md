# Angular Docker (based on Angular 10+)

> By dockerizing your apps, you can easily ship them to any of the cloud providers.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) `version 10.1.6`.

### Dev server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding
Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build
Run `ng build` to build the project.
Build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running end-to-end tests
Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Docker build
To build docker image run `docker build -t angular-docker .`

### Docker run
Run `docker run -d -p 80:80 --env BACKEND_API_URL=yourApiUrl --env DEFAULT_LANGUAGE=de angular-docker` to run docker image
