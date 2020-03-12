# rc-tools-feasin

tools for react component

## Usage

```
$ rc-tools-feasin run lint: run lint by https://github.com/airbnb/javascript
$ rc-tools-feasin run pub: compile and npm publish
$ rc-tools-feasin run watch --out-dir=/xx: watch and compile to /xx, default to lib
$ rc-tools-feasin run build: build examples
$ rc-tools-feasin run gh-pages: push example to gh-pages
$ rc-tools-feasin run start: start dev server
```


package.json demo

```js
({
  config: {
    entry:{}, // webpack entry for build dist umd
    port: 8000, // dev server port
    output:{}, // webpack output for build dist umd
  }
})
```

## History

### 6.0.0

- move test to rc-test
