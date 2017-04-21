# npmtest-dependo

#### basic test coverage for  [dependo (v0.1.6)](https://github.com/auchenberg/dependo.git)  [![npm package](https://img.shields.io/npm/v/npmtest-dependo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dependo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dependo.svg)](https://travis-ci.org/npmtest/node-npmtest-dependo)

#### Visualize your CommonJS, AMD, or ES6 module dependencies.

[![NPM](https://nodei.co/npm/dependo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dependo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dependo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dependo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dependo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dependo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dependo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dependo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dependo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dependo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dependo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dependo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dependo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dependo/build/test-report.html](https://npmtest.github.io/node-npmtest-dependo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dependo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dependo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dependo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dependo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dependo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dependo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dependo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dependo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "dependo",
    "version": "0.1.6",
    "author": "Kenneth Auchecnberg <kenneth@auchenberg.dk>",
    "repository": "https://github.com/auchenberg/dependo.git",
    "homepage": "https://github.com/auchenberg/dependo.git",
    "licenses": [
        {
            "type": "MIT"
        }
    ],
    "description": "Visualize your CommonJS, AMD, or ES6 module dependencies.",
    "keywords": [
        "AMD",
        "RequireJS",
        "require",
        "graph",
        "commonjs",
        "module",
        "circular",
        "dependency",
        "dependencies",
        "visualize",
        "D3",
        "es6"
    ],
    "engines": [
        "node >= 0.10.0"
    ],
    "dependencies": {
        "commander": "~2.6.0",
        "madge": "~0.5.0",
        "sha-1": "^0.1.1",
        "underscore": "~1.7.0"
    },
    "main": "./lib/dependo",
    "bin": {
        "dependo": "./bin/dependo"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
