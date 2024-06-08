# @hishprorg/deleniti-ducimus <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

`Iterator.prototype`, or a shared object to use.

## Usage

```javascript
var iterProto = require('@hishprorg/deleniti-ducimus');
var assert = require('assert');

assert.equal(Object.getPrototypeOf(Object.getPrototypeOf([].keys())), iterProto);
```

[package-url]: https://npmjs.org/package/@hishprorg/deleniti-ducimus
[npm-version-svg]: https://versionbadg.es/hishprorg/deleniti-ducimus.svg
[deps-svg]: https://david-dm.org/hishprorg/deleniti-ducimus.svg
[deps-url]: https://david-dm.org/hishprorg/deleniti-ducimus
[dev-deps-svg]: https://david-dm.org/hishprorg/deleniti-ducimus/dev-status.svg
[dev-deps-url]: https://david-dm.org/hishprorg/deleniti-ducimus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hishprorg/deleniti-ducimus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/deleniti-ducimus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/deleniti-ducimus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishprorg/deleniti-ducimus
[codecov-image]: https://codecov.io/gh/hishprorg/deleniti-ducimus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/hishprorg/deleniti-ducimus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/hishprorg/deleniti-ducimus
[actions-url]: https://github.com/hishprorg/deleniti-ducimus/actions
