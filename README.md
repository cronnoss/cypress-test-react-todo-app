# Build and test an application using Cypress

This repository is the starting point for an official Cypress tutorial. https://github.com/cypress-io/cypress-tutorial-build-todo-starter

https://docs.cypress.io/examples/examples/tutorials.html#Test-a-React-Todo-App

Load the project from the GitHub:
```
git clone https://github.com/cronnoss/cypress-test-react-todo-app.git
```

As soon as project is loaded, go to the root and perform command:
```
npm install
```
It will install all components based on package.json file into node_modules folder.

Launch the server:
```
npm run dev
```
To run all tests in Electron:
```
npx cypress run
```
*If you prefer to see the application GUI while tests execution you may run tests in Chrome.*

To run all tests in Chrome:
```
npx cypress run -b chrome
```
Cypress provides the Test Runner that allows you to run testing files separately and see 
the execution process:  https://docs.cypress.io/guides/core-concepts/test-runner.html#Overview

To open it use the following command:
```
cypress open
```
In the Test Runner you will see the list of testing files. You may click any of them and execution 
tests within a single it would be started in a separate window. Pay attention that results recording 
is not performed if you use the Test Runner. So, this option is mostly for 
development and issues investigation. For running all the scope you should better use other options.
