# cypress-automation-framework

This is e2e automation framework using cypress.io with javascript.This repo contains UI,Analytics and Mocking tests against one of react application. 

![](https://github.com/shyedhu/images/blob/main/cypress-test-run.gif)

## Prerequisites

Install Node.js (together with the NPM tool) by following instructions available on nodejs.org.

## Install

npm (or)

yarn

**1. ** Clone this repo locally:
```console
cd - 

git clone https://github.com/shyedhu/cypress-automation-framework.git

```
navigate into the project folder

cd cypress-automation-framework

and run the following command

```console

npm install

(or)

yarn install --force

```
This will install all of the necessary packages to get cypress installed on your local machine.

## Running tests on chrome browser

```console

npm run cy:run:chrome

(or)

yarn cy:run:chrome

```

## Running tests on firefox browser

```console

npm run cy:run:firefox

(or)

yarn cy:run:firefox

```

## Running tests on chrome headless browser

```console

npm run cy:run:headless

(or)

yarn cy:run:headless

```

## Running tests on docker 

```console

docker build -t cypress-react .

```
