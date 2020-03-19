# node-remove-polyfill
[![npm](https://img.shields.io/npm/v/node-remove-polyfill.svg)](https://www.npmjs.com/package/node-remove-polyfill)
![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/node-remove-polyfill.svg)

A minimal polyfill for [`Node.remove()`](https://developer.mozilla.org/en-US/docs/Web/API/ChildNode/remove), using MDN's implementation. Mostly meant for IE.

## Install
```sh
$ npm install --save node-remove-polyfill
```

## Usage
Pick your favorite:
```js
require('node-remove-polyfill');
```
or
```js
import 'node-remove-polyfill';
```