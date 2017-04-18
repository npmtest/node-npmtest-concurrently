# npmtest-concurrently

#### test coverage for  [concurrently (v3.4.0)](https://github.com/kimmobrunfeldt/concurrently)  [![npm package](https://img.shields.io/npm/v/npmtest-concurrently.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-concurrently) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-concurrently.svg)](https://travis-ci.org/npmtest/node-npmtest-concurrently)

#### Run commands concurrently

[![NPM](https://nodei.co/npm/concurrently.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/concurrently)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-concurrently/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-concurrently/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-concurrently/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-concurrently/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-concurrently/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-concurrently/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-concurrently/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-concurrently/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-concurrently/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-concurrently/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-concurrently/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-concurrently/build/test-report.html](https://npmtest.github.io/node-npmtest-concurrently/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-concurrently/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-concurrently/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-concurrently/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-concurrently/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-concurrently/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-concurrently/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-concurrently/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-concurrently/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kimmo Brunfeldt"
    },
    "bin": {
        "concurrent": "./src/main.js",
        "concurrently": "./src/main.js"
    },
    "bugs": {
        "url": "https://github.com/kimmobrunfeldt/concurrently/issues"
    },
    "dependencies": {
        "chalk": "0.5.1",
        "commander": "2.6.0",
        "date-fns": "^1.23.0",
        "lodash": "^4.5.1",
        "rx": "2.3.24",
        "spawn-command": "^0.0.2-1",
        "supports-color": "^3.2.3",
        "tree-kill": "^1.1.0"
    },
    "description": "Run commands concurrently",
    "devDependencies": {
        "chai": "^1.10.0",
        "mocha": "^2.1.0",
        "mustache": "^1.0.0",
        "releasor": "^1.2.1",
        "semver": "^4.2.0",
        "shell-quote": "^1.4.3",
        "shelljs": "^0.3.0",
        "string": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "60662b3defde07375bae19aac0ab780ec748ba79",
        "tarball": "https://registry.npmjs.org/concurrently/-/concurrently-3.4.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "072bdf20687dec8317181a254a3e5c3dd0467a4b",
    "homepage": "https://github.com/kimmobrunfeldt/concurrently",
    "keywords": [
        "bash",
        "concurrent",
        "parallel",
        "concurrently",
        "command",
        "sh"
    ],
    "license": "MIT",
    "main": "src/main.js",
    "maintainers": [
        {
            "name": "gustavohenke"
        },
        {
            "name": "kimmobrunfeldt"
        }
    ],
    "name": "concurrently",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kimmobrunfeldt/concurrently.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "3.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
