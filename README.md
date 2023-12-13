  # LauncherX

  Open to contributions. If you're an angular dev, let me know!
<div>
   <img src="https://github.com/thankyoufortherecongnitionchair/LaunchPad/assets/77891681/ae7b304b-578d-4bac-af1d-06a318b65f8a" height="50", width="50">
</div>
This project aims to be a library of well crafted, detailed and highly used web-app components that beginners in angular can easily download off of NPM and integrate into their own projects.

# Skeleton:

below is a fairly rudimentary example of how so:

Component Folder named Buttons in master directory (My system)
```html
<button>hello world</button>
```
ordinary export in ts file,
```typescript
module.ts exports it to be built later on using ng cli
import { NgModule } from '@angular/core';
import { AniruddhCompsLibComponent } from './aniruddh-comps-lib.component';
import { ButtonsComponent } from './buttons/buttons.component';

@NgModule({
  declarations: [AniruddhCompsLibComponent, ButtonsComponent],
  imports: [],
  exports: [AniruddhCompsLibComponent, ButtonsComponent],
})
export class AniruddhCompsLibModule {}
```
Now, the button component can easily be imported by users into their systems.

# Angular dev details:
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

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
<hr>
icon by :
<a href="https://www.flaticon.com/free-icons/new-product" title="new product icons">New product icons created by Flat Icons - Flaticon</a>
