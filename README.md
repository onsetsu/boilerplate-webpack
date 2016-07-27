# Boilerplate Webpack [![Build Status](https://travis-ci.org/onsetsu/boilerplate-webpack.svg?branch=master)](https://travis-ci.org/composite-scopes/boilerplate-webpack)
A boilerplate for JavaScript libraries featuring webpack, karma, jasmine, coverage via istanbul and babel6 plugins.

This package still contains all the functionality coming with react and redux in the webpack workflow.

---

**Do not use this for your own projects** as this uses technologies of the last generation of JavaScript engineering (aka Browserify/Webpack). Once we went through the dark ages of JavaScript modules, we can upgrade our projects for simplification of our workflow. However, that day has yet to come.

---

## As Boilerplate

Copy the repo.

```
npm install
```

Replace `boilerplate-webpack` with your package name in *webpack.config.js*.

Run `npm test` to check whether everything worked out.

Adapt as you wish

## Installation

As npm for Node.js:

```
$ npm install boilerplate-webpack --save
```

Or download the [bundle](https://raw.githubusercontent.com/onsetsu/boilerplate-webpack/master/dist/boilerplate-webpack.js) file.

## Building

```
$ npm run-script build
```

creates the *bundle* file in the `dist` folder.

## Testing

As npm package:

```
$ npm test
```
