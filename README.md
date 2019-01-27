# @r3dnag/tiny
Tiny npm module

[![version](https://img.shields.io/npm/v/@r3dnag/tiny.svg)](https://www.npmjs.com/package/@r3dnag/tiny)
![](https://img.shields.io/github/issues/Cyclodex/tiny.svg)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@r3dnag/tiny.svg)](https://www.npmjs.com/package/@r3dnag/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @r3dnag/tiny
```

## Usage

```js
const tiny = require("@r3dnag/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```