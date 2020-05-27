# egg-mq-http-sdk

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/egg-mq-http-sdk.svg?style=flat-square
[npm-url]: https://npmjs.org/package/egg-mq-http-sdk
[travis-image]: https://img.shields.io/travis/eggjs/egg-mq-http-sdk.svg?style=flat-square
[travis-url]: https://travis-ci.org/eggjs/egg-mq-http-sdk
[codecov-image]: https://img.shields.io/codecov/c/github/eggjs/egg-mq-http-sdk.svg?style=flat-square
[codecov-url]: https://codecov.io/github/eggjs/egg-mq-http-sdk?branch=master
[david-image]: https://img.shields.io/david/eggjs/egg-mq-http-sdk.svg?style=flat-square
[david-url]: https://david-dm.org/eggjs/egg-mq-http-sdk
[snyk-image]: https://snyk.io/test/npm/egg-mq-http-sdk/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/egg-mq-http-sdk
[download-image]: https://img.shields.io/npm/dm/egg-mq-http-sdk.svg?style=flat-square
[download-url]: https://npmjs.org/package/egg-mq-http-sdk

<!--
Description here.
-->

## Install

```bash
$ npm i egg-mq-http-sdk --save
```

## Usage

```js
// {app_root}/config/plugin.js
exports.mqHttpSdk = {
  enable: true,
  package: 'egg-mq-http-sdk',
};
```

## Configuration

```js
// {app_root}/config/config.default.js
exports.mqHttpSdk = {
};
```

see [config/config.default.js](config/config.default.js) for more detail.

## Example

<!-- example here -->

## Questions & Suggestions

Please open an issue [here](https://github.com/eggjs/egg/issues).

## License

[MIT](LICENSE)
