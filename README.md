# @taktikorg/corrupti-nostrum-molestias <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@taktikorg/corrupti-nostrum-molestias');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@taktikorg/corrupti-nostrum-molestias
[npm-version-svg]: https://versionbadg.es/inspect-js/@taktikorg/corrupti-nostrum-molestias.svg
[deps-svg]: https://david-dm.org/inspect-js/@taktikorg/corrupti-nostrum-molestias.svg
[deps-url]: https://david-dm.org/inspect-js/@taktikorg/corrupti-nostrum-molestias
[dev-deps-svg]: https://david-dm.org/inspect-js/@taktikorg/corrupti-nostrum-molestias/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@taktikorg/corrupti-nostrum-molestias#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/corrupti-nostrum-molestias.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/corrupti-nostrum-molestias.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/corrupti-nostrum-molestias.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/corrupti-nostrum-molestias
[codecov-image]: https://codecov.io/gh/inspect-js/@taktikorg/corrupti-nostrum-molestias/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@taktikorg/corrupti-nostrum-molestias/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@taktikorg/corrupti-nostrum-molestias
[actions-url]: https://github.com/taktikorg/corrupti-nostrum-molestias/actions
