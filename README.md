# npmtest-karma-jspm

#### basic test coverage for  karma-jspm (v2.2.3)  [![npm package](https://img.shields.io/npm/v/npmtest-karma-jspm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-karma-jspm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-karma-jspm.svg)](https://travis-ci.org/npmtest/node-npmtest-karma-jspm)

#### Include jspm module loader for karma runs; allows dynamic loading of src and test files and modules

[![NPM](https://nodei.co/npm/karma-jspm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/karma-jspm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-karma-jspm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-jspm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-karma-jspm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-karma-jspm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-karma-jspm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-karma-jspm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-karma-jspm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-karma-jspm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-karma-jspm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-jspm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-karma-jspm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-karma-jspm/build/test-report.html](https://npmtest.github.io/node-npmtest-karma-jspm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-karma-jspm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-karma-jspm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-karma-jspm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-karma-jspm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-jspm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-jspm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-karma-jspm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-karma-jspm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "karma-jspm",
    "version": "2.2.3",
    "description": "Include jspm module loader for karma runs; allows dynamic loading of src and test files and modules",
    "main": "index.js",
    "keywords": [
        "karma-plugin",
        "karma-adapter",
        "jspm"
    ],
    "scripts": {
        "test": "cross-env JASMINE_CONFIG_PATH=test/jasmine.json jasmine 'test/**/*.spec.js'",
        "lint": "eslint **/*.js"
    },
    "author": {
        "name": "Max Peterson"
    },
    "contributors": [
        {
            "name": "Max Peterson"
        }
    ],
    "license": "Apache-2.0",
    "repository": {
        "type": "git",
        "url": "git@github.com:Workiva/karma-jspm.git"
    },
    "dependencies": {
        "glob": "~7.0.5"
    },
    "devDependencies": {
        "cross-env": "^1.0.7",
        "eslint": "^2.10.2",
        "jasmine": "^2.4.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
