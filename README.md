# Testes API Cypress

# Automation API Cypress Test

This is the repository for automation of API, developed to work with Cypress.

## Table of Contents

1. [Goal](#goal)
2. [Project Structure](#project-structure)
3. [Tests](#tests)
4. [Initial Setup](#initial-setup)
5. [Run Tests](#run-tests)

## Goal

The goal of this repository is to be easy to understand focused on developing automated tests for API, using [Cypress](https://www.cypress.io/), a tool developed in JavaScript language that provides speed, ease and reliability in the tests.

## Project Structure

```
|--- .github
|----- workflows
|--- cypress
|----- contracts
|----- fixtures
|----- integration
|----- plugins
|----- support
|--- cypress.json
|--- Jenkinsfile
|--- package-lock.json
|--- package.json
```

## Tests

The tests were written using the JavaScript language with Cypress.

## Run tests

### Initial Setup

1. Requires node. To install, execute `npm install node` or download [Node](https://nodejs.org/en/download/)
2. Run the command `npm install` to install dependencies

### Run Tests

- Run one of the commands below to run the tests.
  Examples:
- To run the tests, execute `npm run test` or `cy:run`
- To generate the Mocha reports, execute `npm run cy:report`
- To run the tests generating the Cypress Dashboard, execute `npm run cy:dashboard`
<p>