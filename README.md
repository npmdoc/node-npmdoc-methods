# npmdoc-methods

#### api documentation for  [methods (v1.1.2)](https://github.com/jshttp/methods)  [![npm package](https://img.shields.io/npm/v/npmdoc-methods.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-methods) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-methods.svg)](https://travis-ci.org/npmdoc/node-npmdoc-methods)

#### HTTP methods that node supports

[![NPM](https://nodei.co/npm/methods.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/methods)

- [https://npmdoc.github.io/node-npmdoc-methods/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-methods/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-methods/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-methods/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-methods/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-methods/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "http": false
    },
    "bugs": {
        "url": "https://github.com/jshttp/methods/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        },
        {
            "name": "TJ Holowaychuk",
            "url": "http://tjholowaychuk.com"
        }
    ],
    "dependencies": {},
    "description": "HTTP methods that node supports",
    "devDependencies": {
        "istanbul": "0.4.1",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "5529a4d67654134edcc5266656835b0f851afcee",
        "tarball": "https://registry.npmjs.org/methods/-/methods-1.1.2.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "index.js",
        "HISTORY.md",
        "LICENSE"
    ],
    "gitHead": "25d257d913f1b94bd2d73581521ff72c81469140",
    "homepage": "https://github.com/jshttp/methods",
    "keywords": [
        "http",
        "methods"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "jonathanong"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "dougwilson"
        }
    ],
    "name": "methods",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/methods.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
