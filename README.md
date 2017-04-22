# npmtest-prom-client

#### basic test coverage for  [prom-client (v8.1.1)](https://github.com/siimon/prom-client)  [![npm package](https://img.shields.io/npm/v/npmtest-prom-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-prom-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-prom-client.svg)](https://travis-ci.org/npmtest/node-npmtest-prom-client)

#### Client for prometheus

[![NPM](https://nodei.co/npm/prom-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/prom-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-prom-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-prom-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-prom-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-prom-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-prom-client/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-prom-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-prom-client/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-prom-client/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-prom-client/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-prom-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-prom-client/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-prom-client/build/test-report.html](https://npmtest.github.io/node-npmtest-prom-client/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-prom-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-prom-client/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-prom-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-prom-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-prom-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-prom-client/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-prom-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-prom-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Simon Nyberg"
    },
    "bugs": {
        "url": "https://github.com/siimon/prom-client/issues"
    },
    "dependencies": {
        "tdigest": "^0.1.1",
        "util-extend": "^1.0.1"
    },
    "description": "Client for prometheus",
    "devDependencies": {
        "chai": "^3.4.1",
        "eslint": "^3.5.0",
        "express": "^4.13.3",
        "mocha": "^3.2.0",
        "mockery": "^2.0.0",
        "nock": "^9.0.11",
        "node-version-check": "^2.1.1",
        "sinon": "^2.0.0",
        "typescript": "^2.0.3"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "53f36a6c055360ca0f9dcc8ecc17eca46f00094f",
        "tarball": "https://registry.npmjs.org/prom-client/-/prom-client-8.1.1.tgz"
    },
    "files": [
        "lib/",
        "index.js",
        "index.d.ts"
    ],
    "gitHead": "8c0b408a39970aab899c630b52efe59eab801062",
    "homepage": "https://github.com/siimon/prom-client",
    "keywords": [
        "Prometheus",
        "Metrics",
        "Client"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "siimon"
        }
    ],
    "name": "prom-client",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/siimon/prom-client.git"
    },
    "scripts": {
        "compile-typescript": "tsc index.d.ts --noImplicitAny",
        "lint": "node-version-gte-4 && eslint . || node-version-lt-4",
        "test": "npm run lint && npm run compile-typescript && npm run test-unit",
        "test-unit": "mocha --recursive test/"
    },
    "types": "./index.d.ts",
    "version": "8.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
