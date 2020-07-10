# babel-runtime-corejs3

[![npm][badge-version]][npm]
[![npm downloads][badge-downloads]][npm]
[![license][badge-license]][license]


[![github][badge-issues]][github]
<!--[![build][badge-build]][travis]-->
<!--[![coverage][badge-coverage]][coveralls]-->

## Usage

* Use [babel-runtime@6.x](https://www.npmjs.com/package/babel-runtime/v/6.26.0) with [core-js@3.x](https://www.npmjs.com/package/core-js/v/3.6.5)
* Use both [babel-runtime@6.x](https://www.npmjs.com/package/babel-runtime/v/6.26.0) and [@babel/runtime@7.x](https://www.npmjs.com/package/@babel/runtime/v/7.10.4)

## Get Started

```sh
npm install babel-runtime-corejs3
```

or

```sh
yarn add babel-runtime-corejs3
```

Config your [webpack](https://www.npmjs.com/package/webpack)

```js
resolve: {
  alias: {
    'babel-runtime': 'babel-runtime-corejs3',
  },
},
```

or [rollup](https://www.npmjs.com/package/rollup), using [@rollup/plugin-alias](https://www.npmjs.com/package/@rollup/plugin-alias)

```js
plugins: [
  alias({
    entries: [
      { find: 'babel-runtime', replacement: 'babel-runtime-corejs3' },
    ],
  }),
],
```

[badge-version]: https://img.shields.io/npm/v/babel-runtime-corejs3.svg
[badge-downloads]: https://img.shields.io/npm/dt/babel-runtime-corejs3.svg
[npm]: https://www.npmjs.com/package/babel-runtime-corejs3

[badge-license]: https://img.shields.io/npm/l/babel-runtime-corejs3.svg
[license]: https://github.com/Cweili/babel-runtime-corejs3/blob/master/LICENSE

[badge-issues]: https://img.shields.io/github/issues/Cweili/babel-runtime-corejs3.svg
[github]: https://github.com/Cweili/babel-runtime-corejs3

[badge-build]: https://img.shields.io/travis/com/Cweili/babel-runtime-corejs3/master.svg
[travis]: https://travis-ci.com/Cweili/babel-runtime-corejs3

[badge-coverage]: https://img.shields.io/coveralls/github/Cweili/babel-runtime-corejs3/master.svg
[coveralls]: https://coveralls.io/github/Cweili/babel-runtime-corejs3?branch=master
