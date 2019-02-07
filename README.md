# template-polyfill

[![npm](https://img.shields.io/npm/v/es6-template-polyfill.svg?maxAge=2592000?style=flat-square)](https://www.npmjs.com/package/es6-template-polyfill)

An ES6 importable polyfill for the HTML5 `<template>` tag.

The code is from Brian Blakely's [JSFiddle](http://jsfiddle.net/brianblakely/h3EmY/). Packaged up so that people can use it via npm.

Forked from Jeff Carpenter's [Github](https://github.com/jeffcarp/template-polyfill). Packaged up so that people can use it via npm with ES6 imports.

## Usage

```sh
yarn add template-polyfill
```

```js
import { templatePolyfill } from "es6-template-polyfill"

templatePolyfill()
```

You'll also need to put this in your CSS:

```css
template {
  display: none !important;
}
```
