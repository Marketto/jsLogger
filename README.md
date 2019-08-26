# jsLogger
[![NPM Version](https://img.shields.io/npm/v/@marketto/js-logger.svg)](https://www.npmjs.com/package/@marketto/js-logger)
[![NPM Downloads](https://img.shields.io/npm/dm/@marketto/js-logger.svg)](https://www.npmjs.com/package/@marketto/js-logger)
[![Dependency status](https://david-dm.org/Marketto/jsLogger.svg)](https://david-dm.org/Marketto/jsLogger)
[![Dev dependency status](https://david-dm.org/Marketto/jsLogger/dev-status.svg)](https://david-dm.org/Marketto/jsLogger?type=dev)
[![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=Marketto_jsLogger&metric=alert_status)](https://sonarcloud.io/dashboard/index/Marketto_jsLogger)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=Marketto_jsLogger&metric=coverage)](https://sonarcloud.io/dashboard/index/Marketto_jsLogger)
[![Maintainability](https://sonarcloud.io/api/project_badges/measure?project=Marketto_jsLogger&metric=sqale_rating)](https://sonarcloud.io/dashboard/index/Marketto_jsLogger)
[![Reliability](https://sonarcloud.io/api/project_badges/measure?project=Marketto_jsLogger&metric=reliability_rating)](https://sonarcloud.io/dashboard/index/Marketto_jsLogger)
![Build Status](http://ci.marketto.it/buildStatus/icon?job=js-logger)
[![LICENSE](https://img.shields.io/badge/licese-MIT-gold.svg)](https://github.com/Marketto/jsLogger/blob/master/LICENSE)
[![Blog](https://img.shields.io/badge/blog-marketto-blue.svg)](http://blog.marketto.it)
[![Buy me a coffee](https://img.shields.io/badge/Ko--fi-donate-blueviolet)](https://ko-fi.com/marketto)

Node.js logger utility

## Installation
### Project dependency
```{r, engine='bash', dev_install}
npm install @marketto/js-logger --save
```

## Getting Started
### New Instance
```js
const { Logger } = require("@marketto/js-logger");
const loggerConfig = {
    error: true,
    info: true,
    debug: false,
    warn: true
};
const logger = new Logger(loggerConfig);
```

### Global
```js
const logger = require("@marketto/js-logger").global();

logger.config = {
    error: true,
    info: true,
    debug: false,
    warn: true
};
```

## LICENSE
[MIT License](LICENSE)

## AUTHOR
[Marco Ricupero](mailto:marco.ricupero@gmail.com)
