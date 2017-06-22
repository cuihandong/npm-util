# npm-util
积累一些常用的npmjs库

## 格式类

### numeral

A javascript library for formatting and manipulating numbers.

- [Website and documentation](http://numeraljs.com/)
- [git 地址](https://github.com/adamwdraper/Numeral-js.git)

#### 安装
```bash
$ npm install numeral --save
```

- - -


### dateformat

A node.js package for Steven Levithan's excellent [dateFormat()](http://blog.stevenlevithan.com/archives/date-time-format) function.
- [git 地址](https://github.com/felixge/node-dateformat.git)

#### Installation

```bash
$ npm install dateformat
$ dateformat --help
```

- - -

### decamelize [![Build Status](https://travis-ci.org/sindresorhus/decamelize.svg?branch=master)](https://travis-ci.org/sindresorhus/decamelize)

> Convert a camelized string into a lowercased one with a custom separator<br>
> Example: `unicornRainbow` → `unicorn_rainbow`
- [git 地址](https://github.com/sindresorhus/decamelize.git)

#### Install

```
$ npm install --save decamelize
```


#### Usage

```js
const decamelize = require('decamelize');

decamelize('unicornRainbow');
//=> 'unicorn_rainbow'

decamelize('unicornRainbow', '-');
//=> 'unicorn-rainbow'
```
