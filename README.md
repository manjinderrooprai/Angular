# Angular
Welcome to the Angular PoCs (Proof of Concepts) repository! This repository serves as a collection of Angular Proof of Concepts, demonstrating various features, techniques, and integrations within Angular applications.

[Angular 17](https://angular.dev/)

## Angular 17 Key Features
1. **Standalone Components by Default:** This simplifies application structure. You can create components without the need for an Ngmodule, potentially leading to cleaner code and faster development.
2. **Strict Templates:** Angular 17 enforces stricter templates by default. This helps catch errors early in the development process, leading to more robust applications.
3. **Improved Language Service:** The language service in Angular 17 provides better autocompletion, diagnostics, and navigation within your Angular templates. This can significantly improve development speed and code quality.
4. **Optional Chaining in Templates:** Optional chaining allows you to safely access properties of potentially nullish values within your templates. This helps prevent errors and improves code readability.
5. **Enhanced Performance with Differential Loading:** Angular 17 improves bundle splitting by allowing for differential loading. This means only the necessary code is loaded for a specific route or feature, leading to faster initial load times for your application.
   
## Prerequisites
**Node.js and npm:** Angular relies on Node.js and npm (Node Package Manager) to run. Download and install the latest version of Node.js from the official website https://nodejs.org/en/download. This will also install npm.

### Install the Angular CLI:
- Open the integrated terminal in VS Code (Terminal > New Terminal) or System Terminal.
- Run the following command to install the **Angular CLI globally:**
  `npm install -g @angular/cli`

### Setup
1. **Clone the Repository:**
   `git@github.com:manjinderrooprai/Angular.git`
2. **Open Directory:**
   `cd ~/Angular`
3. **Open Project in Vscode:**
   `code .`
4. **Go to specific project directory:**
   `cd Specific-project`
5. **Install dependencies:**
   `npm install`
6. **Run the development server:**
   `ng serve`
   
Once the application has started, you can access it by opening a web browser and navigating to http://localhost:8000](https://locall.host/4200/ (assuming the application runs on port 4200).

**NOTE:** The app will automatically reload if you change any of the source files.

## Development Server
Angular utilizes the Angular CLI for development tasks. You can use the following commands:

* **Development server:** ng serve
* **Build:** ng build
* **Unit tests:** ng test
* **End-to-end tests:** ng e2e

## Json Server
1. **Install** `npm install json-server`
2. **Create a db.json or db.json5 file:**
```{ "employees":[
  {
    "id": 1,
    "firstName": "Santhosh",
    "lastName": "Vernekar",
    "age": 30,
    "email": "santosh@gmail.com",
    "phoneNumber": "9999999999",
    "address": "111-5770 Hastings st, burnaby, bc, canada"
  },
  {
    "id": 2,
    "firstName": "Virat",
    "lastName": "Kohli",
    "age": 28,
    "email": "Virat@gmail.com",
    "phoneNumber": "9999999900",
    "address": "111-5777 Hastings st, burnaby, bc, canada"
  }
]
}```
3. **Run Sever:** 'npx json-server db.json'
4. **Get a REST API**
```$ curl http://localhost:3000/employees/1
{
  "id": "1",
  "title": "a title"
}```

## Projcet Structure
**The project follows a standard Angular folder structure.**
- **src/:** Contains the source files for the Angular application.
    - **app/:** Contains the components, modules, services, and other Angular elements.
    - **assets/:** Contains static assets like images, fonts, etc.
    - **environments/:** Contains environment-specific configuration files.

    This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.0.
