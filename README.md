# Webpack Boilerplate

[![Build Status](https://travis-ci.org/NeverMendel/webpack-boilerplate.svg?branch=master)](https://travis-ci.org/NeverMendel/webpack-boilerplate)

> Webpack Boilerplate with TypeScript, CSS and Prettier support

## Requirement

You need npm and git installed on your system. Click [here](https://www.npmjs.com/get-npm) more info on how to install npm.

## Features

- [TypeScript](https://www.typescriptlang.org/)

- CSS support via [css-loader](https://github.com/webpack-contrib/css-loader)

- [Prettier](https://prettier.io/)

## Get started

### Install

First, clone the repo via git:

```bash
git clone --depth 1 --single-branch --branch master https://github.com/NeverMendel/webpack-boilerplate.git your-project-name
```

And then install the dependencies with npm:

```bash
cd your-project-name
npm install
```

### Development

To run locally the server on the port 8080 (<http://localhost:8080>) execute:

```bash
npm start
```

### Deployment

Build the application:

```bash
npm run build
```

The output will be in the `public` folder.
