# GitHub Codespaces E2E Test Scenario: Static Web App

## Setup

1. Install the Azure Functions extension

1. Run the following to install Azure Functions Core Tools

    ```
    npm i -g azure-functions-core-tools@3 --unsafe-perm true
    ```

## Run the application

1. The frontend is a React app which is run with...

    ```
    npm start
    ```

1.  The backend is a Functions project that should be started from the run and debug panel.

## Forward ports

1. Forward ports 3000 and 7071