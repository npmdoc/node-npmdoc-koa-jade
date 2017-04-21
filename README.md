# npmdoc-koa-jade

#### api documentation for  [koa-jade (v2.1.0)](https://github.com/chrisyip/koa-jade)  [![npm package](https://img.shields.io/npm/v/npmdoc-koa-jade.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-koa-jade) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-koa-jade.svg)](https://travis-ci.org/npmdoc/node-npmdoc-koa-jade)

#### A Jade middleware for Koa

[![NPM](https://nodei.co/npm/koa-jade.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-jade)

- [https://npmdoc.github.io/node-npmdoc-koa-jade/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-jade/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-jade/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-koa-jade/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-koa-jade/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "koa-jade",
    "version": "2.1.0",
    "description": "A Jade middleware for Koa",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/chrisyip/koa-jade.git"
    },
    "bugs": {
        "url": "https://github.com/chrisyip/koa-jade/issues"
    },
    "homepage": "https://github.com/chrisyip/koa-jade",
    "scripts": {
        "lint": "./node_modules/.bin/eslint .",
        "mocha": "node --harmony node_modules/istanbul/lib/cli.js cover node_modules/mocha/bin/_mocha --bail --check-leaks test/",
        "test": "npm run lint && npm run mocha"
    },
    "keywords": [
        "koa",
        "jade",
        "template"
    ],
    "author": {
        "name": "Chris Yip"
    },
    "license": "MIT",
    "dependencies": {
        "fs-extra": "^0.24.0",
        "jade": "^1.11.0",
        "lodash": "^3.10.1"
    },
    "devDependencies": {
        "bluebird": "^2.9.34",
        "chai": "^3.2.0",
        "cheerio": "^0.19.0",
        "eslint": "^1.10.2",
        "istanbul": "^0.3.19",
        "jstransformer-markdown-it": "^0.1.0",
        "koa": "^1.0.0",
        "koa-route": "^2.4.2",
        "koa-vhost": "^0.5.0",
        "marked": "^0.3.5",
        "mocha": "^2.3.0",
        "supertest": "^1.1.0",
        "supertest-koa-agent": "^0.2.1"
    },
    "engines": {
        "node": ">=0.11.9"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
