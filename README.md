# is-js-array [![NPM version](https://img.shields.io/npm/v/is-js-array.svg?style=flat)](https://www.npmjs.com/package/is-js-array)

> Returns true if the value is an array

## Installation

Install with [npm](https://www.npmjs.com/):

```sh
npm i is-js-array
```

## Usage

```js
const { isJSArray } = require("is-js-array");
```

### true

```js
isJSArray([]); // true
isJSArray([1, 2]); // true
```

### false

```js
isJSArray({}); // false
isJSArray("Not an Array"); // false
```
