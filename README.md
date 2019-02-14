# Optilyz Interview Task

This project template was built with [Create React App](https://github.com/facebookincubator/create-react-app). Project is build based on react and redux.

## Run app

In the project directory, you can run:

`yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Tasks
1. Tests
    Jest is installed and to run tests use: `yarn test`
    * write test for one component
    * write test for one container
2. Define and fix bugs
    * add 2 items with the same text and check one of them
    * add 5 items (2 completed, 3 not completed) and play with the filter

3. Implement feature
    * clear all completed tasks from list

4. Routing

    Module `react-router-dom` is already added in package.json
    * completed task should be shown with the path `/completed`
    * active task should be show with the path `/active`



5. Async call
    * implement autocomplete on focus input to add a task
    * fetch a list from http://localhost:3000/autocomplete.json
    * show list before typing
    * when user selects an option, replace input content with selected text

6. Improve interface using "styled-components"
    * install styled-components
    * beautify buttons, input, list
