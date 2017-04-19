# npmtest-tcomb

#### test coverage for  [tcomb (v3.2.20)](https://github.com/gcanti/tcomb)  [![npm package](https://img.shields.io/npm/v/npmtest-tcomb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tcomb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tcomb.svg)](https://travis-ci.org/npmtest/node-npmtest-tcomb)

#### Type checking and DDD for JavaScript

[![NPM](https://nodei.co/npm/tcomb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tcomb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tcomb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tcomb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tcomb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tcomb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tcomb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tcomb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tcomb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tcomb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tcomb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tcomb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tcomb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tcomb/build/test-report.html](https://npmtest.github.io/node-npmtest-tcomb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tcomb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tcomb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tcomb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tcomb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tcomb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tcomb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tcomb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tcomb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Giulio Canti"
    },
    "bugs": {
        "url": "https://github.com/gcanti/tcomb/issues"
    },
    "dependencies": {},
    "description": "Type checking and DDD for JavaScript",
    "devDependencies": {
        "benchmark": "2.1.0",
        "eslint": "1.10.3",
        "mocha": "2.3.4",
        "webpack": "1.12.14"
    },
    "directories": {},
    "dist": {
        "shasum": "823e689dcf3518d82c4b6c890a822aa6916692cd",
        "tarball": "https://registry.npmjs.org/tcomb/-/tcomb-3.2.20.tgz"
    },
    "files": [
        "index.js",
        "lib",
        "index.d.ts"
    ],
    "gitHead": "d231ed7b1bb1f2082451543cba5b813fef78e1db",
    "homepage": "https://github.com/gcanti/tcomb",
    "keywords": [
        "type",
        "combinators",
        "checking",
        "safety",
        "model",
        "domain",
        "debugging",
        "immutable",
        "DDD",
        "JSON",
        "store"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "gcanti"
        }
    ],
    "name": "tcomb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gcanti/tcomb.git"
    },
    "scripts": {
        "dist": "webpack",
        "lint": "eslint index.js lib test",
        "perf": "node ./perf/perf",
        "test": "npm run lint && mocha"
    },
    "tags": [
        "type",
        "combinators",
        "checking",
        "safety",
        "model",
        "domain",
        "debugging",
        "immutable",
        "DDD",
        "JSON",
        "store"
    ],
    "typings": "index.d.ts",
    "version": "3.2.20"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
