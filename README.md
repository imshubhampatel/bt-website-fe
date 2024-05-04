# bt-website-fe

The College Management Dashboard for Babulal Tarabai Institute of Research and Technology (BTIRT) is a comprehensive web application designed to streamline administrative tasks and enhance communication within the college community. This dashboard serves as a centralized platform to manage various aspects of college life, including academic activities, sports, events, and social gatherings. [Repository Link](https://github.com/imshubhampatel/bt-website-fe.git). 

## Installation


To get started, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/imshubhampatel/bt-website-fe.git
   ```

2. Navigate to project directory:

   ```bash
   cd bt-website-fe
   ```
3. Install dependencies using Yarn:
   ```bash
   yarn install
   ```
   

## Available Scripts
In the project directory, you can run the following scripts:

+ #### Development: 


  ```
   yarn dev
  ```
  Starts the development server using Vite.
+ #### Build: 

  ```
   yarn build
  ```
  Builds the app for production.
+ #### Lint & Validation: 

  ```
   yarn lint
  ```
  Runs ESLint to check for code style and formatting issues
+ #### Format Code: 

  ```
   yarn format
  ```
  Formats the source code using Prettier.
+ #### Check Code Formatting: 

  ```
   yarn format:check
  ```
  Previews the production build locally
 

## Pre-commit Hooks

Before making a commit, the following tasks will be automatically executed:
 - Code formatting using Prettier [( yarn format )](https://www.npmjs.com/package/prettier)
 - Code formatting check [( yarn format:check )](https://www.npmjs.com/package/prettier)
 - Code linting [( yarn lint )](https://www.npmjs.com/package/eslint)
 

## Dependencies

- ```axios```: Promise-based HTTP client for making API requests.
- ```moment```: Library for parsing, validating, manipulating, and formatting dates.
- ```react```: JavaScript library for building user interfaces.
- ```react-dom```: Entry point to the DOM and server renderers for React components.



## Development Dependencies

- ```@types/react:``` TypeScript type definitions for React.
- ```@types/react-dom```: TypeScript type definitions for React DOM.
- ```@vitejs/plugin-react```: Vite plugin for React integration.
- ```eslint```: JavaScript and TypeScript code linter.
- ```eslint-plugin-react```: ESLint plugin for React specific linting rules.
- ```eslint-plugin-react-hooks```: ESLint plugin for React Hooks rules.
- ```eslint-plugin-react-refresh```: ESLint plugin for React Refresh.
- ```pre-commit```: Git hook tool to manage and run pre-commit tasks.
- ```prettier```: Opinionated code formatter.

