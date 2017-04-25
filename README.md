# npmdoc-coffee

#### basic api documentation for  [coffee (v3.3.0)](https://github.com/popomore/coffee)  [![npm package](https://img.shields.io/npm/v/npmdoc-coffee.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-coffee) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-coffee.svg)](https://travis-ci.org/npmdoc/node-npmdoc-coffee)

#### Test command line on nodejs

[![NPM](https://nodei.co/npm/coffee.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/coffee)

- [https://npmdoc.github.io/node-npmdoc-coffee/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-coffee/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-coffee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-coffee/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-coffee/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-coffee/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "popomore"
    },
    "bugs": {
        "url": "https://github.com/popomore/coffee/issues"
    },
    "dependencies": {
        "childprocess": "~2.0.0",
        "debug": "~2.2.0"
    },
    "description": "Test command line on nodejs",
    "devDependencies": {
        "autod": "2",
        "eslint": "2",
        "eslint-config-egg": "^2.0.0",
        "istanbul": "0",
        "mm": "^1.3.5",
        "mocha": "2",
        "should": "6",
        "spy": "^0.1.3"
    },
    "directories": {},
    "dist": {
        "shasum": "3cd8ec513427b4b301573caa0640c031172ae4f6",
        "tarball": "https://registry.npmjs.org/coffee/-/coffee-3.3.0.tgz"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "2c947901cf75f4360fc582c0ea34ebc99617adf5",
    "homepage": "https://github.com/popomore/coffee",
    "keywords": [
        "test",
        "shell",
        "spawn",
        "fork",
        "child_process",
        "exec"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fengmk2"
        },
        {
            "name": "popomore"
        }
    ],
    "name": "coffee",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/popomore/coffee.git"
    },
    "scripts": {
        "autod": "autod -e test/fixtures -f ~ -w",
        "clean": "rm -rf coverage",
        "cov": "npm run clean && npm run lint && npm run cover && istanbul report --root coverage text-summary json lcov",
        "cover": "rm -rf coverage && istanbul cover --report none --print none node_modules/mocha/bin/_mocha -- -R spec -t 80000",
        "lint": "eslint index.js lib test",
        "test": "mocha -R spec -t 80000"
    },
    "version": "3.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
