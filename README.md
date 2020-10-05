# @cjonnpm/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@cjonnpm/tiny.svg)](https://github.com/cjongithub/tiny) [![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@cjonnpm/tiny.svg)](https://github.com/cjongithub/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @cjonnpm/tiny
```

## Usage

```js
const tiny = require('@cjonnpm/tiny');

tiny('So much space!');
//=> 'Somuchspace!'

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```