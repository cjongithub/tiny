# @cjonnpm/tiny

[![npm (scoped)](https://img.shields.io/badge/npm-v1.0.0-blue)](https://github.com/cjongithub/tiny) [![npm bundle size (minified)](https://img.shields.io/badge/minified%20size-entry%20point%20error-red)](https://github.com/cjongithub/tiny)

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