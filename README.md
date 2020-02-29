# rb-tools

offline tools for react component

[![NPM version][npm-image]][npm-url]
[![gemnasium deps][gemnasium-image]][gemnasium-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]
[![david-dm][david-image]][david-url]

[npm-image]: http://img.shields.io/npm/v/rb-tools.svg?style=flat-square
[npm-url]: http://npmjs.org/package/rb-tools
[travis-image]: https://img.shields.io/travis/react-component/rb-tools.svg?style=flat-square
[travis-url]: https://travis-ci.org/react-component/rb-tools
[coveralls-image]: https://img.shields.io/coveralls/react-component/rb-tools.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/react-component/rb-tools?branch=master
[gemnasium-image]: http://img.shields.io/gemnasium/react-component/rb-tools.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/react-component/rb-tools
[node-image]: https://img.shields.io/badge/node.js-%3E=_0.11-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/rb-tools.svg?style=flat-square
[download-url]: https://npmjs.org/package/rb-tools
[david-image]: https://david-dm.org/react-component/rb-tools.svg
[david-url]: https://david-dm.org/react-component/rb-tools

## Usage

```
$ rb-tools run lint: run lint by https://github.com/airbnb/javascript
$ rb-tools run pub: compile and npm publish
$ rb-tools run watch --out-dir=/xx: watch and compile to /xx, default to lib
$ rb-tools run build: build examples
$ rb-tools run gh-pages: push example to gh-pages
$ rb-tools run start: start dev server
```

package.json demo

```js
({
  config: {
    entry: {}, // webpack entry for build dist umd
    port: 8000, // dev server port
    output: {}, // webpack output for build dist umd
  },
});
```

## History

### 9.0.0

- upgrade all deps
- add `test` task

### 8.0.0

- upgrade eslint to the latest version
- introduce prettier

### 7.0.0

- upgrade to webpack3

### 6.0.0

- move test to rc-test
