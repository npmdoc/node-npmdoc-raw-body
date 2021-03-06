# npmdoc-raw-body

#### api documentation for  [raw-body (v2.2.0)](https://github.com/stream-utils/raw-body#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-raw-body.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-raw-body) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-raw-body.svg)](https://travis-ci.org/npmdoc/node-npmdoc-raw-body)

#### Get and validate the raw body of a readable stream.

[![NPM](https://nodei.co/npm/raw-body.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/raw-body)

- [https://npmdoc.github.io/node-npmdoc-raw-body/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-raw-body/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-raw-body/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-raw-body/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-raw-body/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-raw-body/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/stream-utils/raw-body/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Raynos"
        }
    ],
    "dependencies": {
        "bytes": "2.4.0",
        "iconv-lite": "0.4.15",
        "unpipe": "1.0.0"
    },
    "description": "Get and validate the raw body of a readable stream.",
    "devDependencies": {
        "bluebird": "3.4.7",
        "eslint": "3.12.2",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-markdown": "1.0.0-beta.3",
        "eslint-plugin-promise": "3.4.0",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "readable-stream": "2.1.2",
        "through2": "2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "994976cf6a5096a41162840492f0bdc5d6e7fb96",
        "tarball": "https://registry.npmjs.org/raw-body/-/raw-body-2.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "02fac48ae40b8452629bcd310d19dbea543f7c3c",
    "homepage": "https://github.com/stream-utils/raw-body#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "jongleberry"
        }
    ],
    "name": "raw-body",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stream-utils/raw-body.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --trace-deprecation --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --trace-deprecation --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --trace-deprecation --reporter spec --check-leaks test/"
    },
    "version": "2.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
