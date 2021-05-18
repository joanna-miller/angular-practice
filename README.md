# _Angular Practice_

### By _**Jo Miller**_

#### _This project was created solely for the education of the author and is not in a complete or portfolio-ready state. It should not be considered representative of professional work._

#### Date created: 05/17/2021
---

## Technologies Used

* _Angular 11.2.14_
* _TypeScript 4.1.5_
* _Firebase 8.6.1_
* _Angular Material 11.2.12_
* _Angular Router 11.2.13_
* _git 2.30.0_

---

## Description

This is a practice project created solely to explore Angular as a beginner. I used it to practice implementing routing, Angular Material, and authentication via Firebase.

---

## Setup/Installation

* You will need to use your system's **terminal emulator** to setup and locally use this application.
* This project uses npm as a package manager, you can download it [here](https://www.npmjs.com/get-npm).
* To clone this directory, navigate in your terminal to the desired location of the project and run command `git clone https://github.com/joanna-miller/angular-practice.git`
* Navigate to top level of the directory with command `cd angular-practice`
* To install dependencies into the project run command `npm install`
* To set up Firebase, start by creating a Firebase project [here](https://firebase.google.com/).
* Create an `environments` directory in the src folder with a file named `environment.ts`
* Add your firebase configuration in environment.ts file as follows: 
```
export const environment = {
  production: false,
  firebase: {
    apiKey: "xxxxxxxx-xxxxxxxx",
    authDomain: "xxxxxxxxxxxxxxxxxxxxxxxx",
    databaseURL: "xxxxxxxxxxxxxxxxxxxxxxxx",
    projectId: "xxxxxxxx",
    storageBucket: "xxxxxxxx",
    messagingSenderId: "xxxxxx",
    appId: "xxxxx",
    measurementId: "xxxxxxxxxxxxxxxx"
  }
};
```
* To launch this project in a browser, run command `ng serve` and navigate to http://localhost:4200/
* To exit live server, press Ctrl+C in your terminal

--- 

## Editing Instructions

* To use Visual Studio Code to edit this project, follow install instructions [here](https://code.visualstudio.com/).
* To enable command `code`, open VS Code, click on View > Command Palette, type in "shell command", and click on "Shell Command: Install 'code' command in PATH"
* Now, from your terminal, in the project's top level directory, you can run command `code .` to open project in VS Code.

---

## License

[MIT](LICENSE.txt)

---

## Contact Information

* _Contact Jo via [Email](mailto:joannadawnmiller@gmail.com) or [LinkedIn](https://www.linkedin.com/in/jomillerde/), or check out her [Github](https://github.com/joanna-miller)._
