# jsLogger
[![NPM Version](http://img.shields.io/npm/v/@marketto/js-logger.svg?style=flat)](https://www.npmjs.org/package/@marketto/js-logger)
[![NPM Downloads](https://img.shields.io/npm/dm/@marketto/js-logger.svg?style=flat)](https://npmcharts.com/compare/@marketto/js-logger?minimal=true)
[![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=Marketto_jsLogger&metric=alert_status)](https://sonarcloud.io/dashboard/index/Marketto_jsLogger)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=Marketto_jsLogger&metric=coverage)](https://sonarcloud.io/dashboard/index/Marketto_jsLogger)
[![Maintainability](https://sonarcloud.io/api/project_badges/measure?project=Marketto_jsLogger&metric=sqale_rating)](https://sonarcloud.io/dashboard/index/Marketto_jsLogger)
[![Reliability](https://sonarcloud.io/api/project_badges/measure?project=Marketto_jsLogger&metric=reliability_rating)](https://sonarcloud.io/dashboard/index/Marketto_jsLogger)
![Build Status](http://ci.marketto.it/buildStatus/icon?job=js-logger)

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