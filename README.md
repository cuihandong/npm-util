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
