# test coverage for  [html-entities (v1.2.0)](https://github.com/mdevils/node-html-entities#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-html-entities.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html-entities) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html-entities.svg)](https://travis-ci.org/npmtest/node-npmtest-html-entities)
#### Faster HTML entities encode/decode library.

[![NPM](https://nodei.co/npm/html-entities.png?downloads=true)](https://www.npmjs.com/package/html-entities)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html-entities/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-entities/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html-entities/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html-entities/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html-entities/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html-entities/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html-entities/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-entities/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-html-entities/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-html-entities/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-html-entities%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html-entities/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-entities/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-html-entities%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-entities/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html-entities/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html-entities/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marat Dulin",
        "email": "mdevils@yandex.ru"
    },
    "bugs": {
        "url": "https://github.com/mdevils/node-html-entities/issues"
    },
    "dependencies": {},
    "description": "Faster HTML entities encode/decode library.",
    "devDependencies": {
        "chai": "^1.9.1",
        "coveralls": "^2.11.2",
        "entities": "*",
        "mocha": "^1.21.4",
        "node-html-encoder": "*",
        "unit-coverage": "^3.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "41948caf85ce82fed36e4e6a0ed371a6664379e2",
        "tarball": "https://registry.npmjs.org/html-entities/-/html-entities-1.2.0.tgz"
    },
    "engines": [
        "node >= 0.4.0"
    ],
    "files": [
        "index.js",
        "lib",
        "LICENSE"
    ],
    "gitHead": "3a2cd397697c872325f526bb422bdee74f089cda",
    "homepage": "https://github.com/mdevils/node-html-entities#readme",
    "keywords": [
        "html",
        "html entities",
        "html entities encode",
        "html entities decode",
        "entities",
        "entities encode",
        "entities decode"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "mdevils",
            "email": "mdevils@yandex.ru"
        }
    ],
    "name": "html-entities",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mdevils/node-html-entities.git"
    },
    "scripts": {
        "benchmark": "node benchmark/benchmark",
        "coverage": "unit-coverage run -p common",
        "coverage-html": "unit-coverage run -p common -r html -o coverage.html",
        "test": "mocha --recursive -R spec test",
        "travis": "npm test && unit-coverage run -p common -r lcov -o coverage.lcov && cat coverage.lcov | coveralls"
    },
    "unit-coverage": {
        "common": [
            "-s",
            "lib/**/*.js",
            "-t",
            "test/**/*.js"
        ]
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
