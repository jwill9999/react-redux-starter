# React Redux Flow Starter Kit



![](./public/images/starterkit-1.png)

## Description

This starter kit contains the following technology setup

> React

> Routing

> Redux

> Flow config

> Eslint config

> Airbnb linting rules

> Jest/Enzyme setup

> Node Server intergration


## Download

```
>  git Clone <repo>

>  cd client

>  yarn install

>  yarn start or npm start

 localhost: port 3000

```

 

# Eslint Configuration files

> Edit .eslintrc file

Here you can add or remove your own linting rules. The linter is setup to work with prettier. To add and remove own rules edit the rules section.

## Link > [Eslint Available Rules](https://eslint.org/docs/rules/)


# Flow Configuration files

> Edit .flowconfig file

Here you can add or remove your own type rules. The staic typings is setup to work with react. To add and remove own rules edit this file.

## To run flow

You can add an extension to your editor of choice which will run a flow server in the editor or alternatively follow the link below for cli commands 'flow status' && 'flow stop'

## Link > [Flow Commands](https://flow.org/en/docs/usage/)


## Link  > [Flow Configuration ](https://flow.org/en/docs/config/)


# Testing Configuration files

> src/\_\_tests_\_

Here you can add or remove your own jest tests. The test suite is setup to work with React . To add ayour own test add them here in accordance with jest file naming guidelines.

Enzyme is also included and to make life easier the Enzyme configuration file is included here ... 

> src/setupTests.js

## Link > [Jest documentation](https://jestjs.io/)

## Link > [Enzyme documentation](https://airbnb.io/enzyme/)

# Routing Configuration files

## Routing structure

Routing is configured in the following folder using react router dom 4

> src/App/App.js

You can add your routes to this folder above

Unknown routes are routed to component ErrorPage. Feel free to style your own 404 page within the 

> src/components/ErrorPage

Please note that the Provider tag for the redux store has been extracted to a separtate file and imported into the router here as <Root>. This is for the purpose of testing as we will need the Provider and store within our testing suite to make them work as expected.

### Redux Provider 

> src/RootProvider.js



