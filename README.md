# rb-tools

offline tools for react component

## Usage

```
$ rb-tools run lint: run lint by https://github.com/airbnb/javascript
$ rb-tools run pub: compile and npm publish
$ rb-tools run watch --out-dir=/xx: watch and compile to /xx, default to lib
$ rb-tools run build: build examples
$ rb-tools run gh-pages: push example to gh-pages
$ rb-tools run start: start dev server
```

## package.json demo

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
