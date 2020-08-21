# @andres-cruz/tiny

![npm (scoped)](https://img.shields.io/npm/v/@andres-cruz/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @andres-cruz/tiny
```

## Usage

```js
const tiny = require('@andres-cruz/tiny');

tiny('So much space!');
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
