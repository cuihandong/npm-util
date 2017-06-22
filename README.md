# npm-util
积累一些常用的npmjs库

注：编写md文档请参考[《Markdown 入门参考》](http://xianbai.me/learn-md/index.html)

## 目录


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
### camelcase

> Convert a dash/dot/underscore/space separated string to camelCase: `foo-bar` → `fooBar`
- [git 地址](https://github.com/sindresorhus/camelcase.git)

#### Install

```
$ npm install --save camelcase
```


#### Usage

```js
const camelCase = require('camelcase');

camelCase('foo-bar');
//=> 'fooBar'

camelCase('foo_bar');
//=> 'fooBar'

camelCase('Foo-Bar');
//=> 'fooBar'

camelCase('--foo.bar');
//=> 'fooBar'

camelCase('__foo__bar__');
//=> 'fooBar'

camelCase('foo bar');
//=> 'fooBar'

console.log(process.argv[3]);
//=> '--foo-bar'
camelCase(process.argv[3]);
//=> 'fooBar'

camelCase('foo', 'bar');
//=> 'fooBar'

camelCase('__foo__', '--bar');
//=> 'fooBar'
```

- - -

### decamelize

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

## 程序流

### async
![Async Logo](https://raw.githubusercontent.com/caolan/async/master/logo/async-logo_readme.jpg)

[![Build Status via Travis CI](https://travis-ci.org/caolan/async.svg?branch=master)](https://travis-ci.org/caolan/async)
[![NPM version](https://img.shields.io/npm/v/async.svg)](https://www.npmjs.com/package/async)
[![Coverage Status](https://coveralls.io/repos/caolan/async/badge.svg?branch=master)](https://coveralls.io/r/caolan/async?branch=master)
[![Join the chat at https://gitter.im/caolan/async](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/caolan/async?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![libhive - Open source examples](https://www.libhive.com/providers/npm/packages/async/examples/badge.svg)](https://www.libhive.com/providers/npm/packages/async)

Async is a utility module which provides straight-forward, powerful functions for working with asynchronous JavaScript. Although originally designed for use with [Node.js](https://nodejs.org/) and installable via `npm install --save async`, it can also be used directly in the browser.

For Documentation, visit <https://caolan.github.io/async/>

*For Async v1.5.x documentation, go [HERE](https://github.com/caolan/async/blob/v1.5.2/README.md)*

*<https://github.com/caolan/async.git>*
