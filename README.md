# npmtest-bn.js

#### basic test coverage for  [bn.js (v4.11.6)](https://github.com/indutny/bn.js)  [![npm package](https://img.shields.io/npm/v/npmtest-bn.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bn.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bn.js.svg)](https://travis-ci.org/npmtest/node-npmtest-bn.js)

#### Big number implementation in pure javascript

[![NPM](https://nodei.co/npm/bn.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bn.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bn.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bn.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bn.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bn.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bn.js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-bn.js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-bn.js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bn.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bn.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bn.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bn.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bn.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bn.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bn.js/build/test-report.html](https://npmtest.github.io/node-npmtest-bn.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bn.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bn.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bn.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bn.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bn.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bn.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bn.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bn.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fedor Indutny"
    },
    "bugs": {
        "url": "https://github.com/indutny/bn.js/issues"
    },
    "dependencies": {},
    "description": "Big number implementation in pure javascript",
    "devDependencies": {
        "istanbul": "^0.3.5",
        "mocha": "^2.1.0",
        "semistandard": "^7.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "53344adb14617a13f6e8dd2ce28905d1c0ba3215",
        "tarball": "https://registry.npmjs.org/bn.js/-/bn.js-4.11.6.tgz"
    },
    "gitHead": "e4a82134c89ed85b0c3a03da7fabc016206898a4",
    "homepage": "https://github.com/indutny/bn.js",
    "keywords": [
        "BN",
        "BigNum",
        "Big number",
        "Modulo",
        "Montgomery"
    ],
    "license": "MIT",
    "main": "lib/bn.js",
    "maintainers": [
        {
            "name": "cwmma"
        },
        {
            "name": "dcousens"
        },
        {
            "name": "indutny"
        }
    ],
    "name": "bn.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/indutny/bn.js.git"
    },
    "scripts": {
        "lint": "semistandard",
        "test": "npm run lint && npm run unit",
        "unit": "mocha --reporter=spec test/*-test.js"
    },
    "version": "4.11.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
