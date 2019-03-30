# @jlp0422/tiny

![npm (scoped)](https://img.shields.io/npm/v/@jlp0422/tiny.svg)

It's v tiny

Removes all spaces from a string.

## Install

```
$ npm install @jlp0422/tiny
```

## Usage

```js
const tiny = require("@jlp0422/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
