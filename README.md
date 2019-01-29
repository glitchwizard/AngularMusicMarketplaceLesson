# AngularMusicMarketplaceLesson

This project is an exercise from Epicodus to create a music marketplace with Angular Routing implemented.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Use Firebase for database, navigate to: firebase.google.com
  **Creating an Account**
   First off, you'll need to make a free account at Firebase's website.

  **Creating a Project**
  Next, create a remote database for our application through Firebase's website.

  Once you've created an account, you should be taken to a user dashboard area, with an option to Create a New Project. Select this option, provide a name for your new project, and select your Country/region from the drop-down menu.

  You'll then be taken to an "Overview" area. Where you'll be offered three options:

  Add Firebase to your iOS app
  Add Firebase to your Android app
  Add Firebase to your web app
  Select Add Firebase to your web app. Firebase should respond with a pop-up modal window.

  Update **src/app/api-keys.ts** with the information from the modal window that popped up: 
  _export const masterFirebaseConfig = {
      apiKey: "xxxx",
      authDomain: "xxxx.firebaseapp.com",
      databaseURL: "https://xxxx.firebaseio.com",
      storageBucket: "xxxx.appspot.com",
      messagingSenderId: "xxxx"
    };_

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
