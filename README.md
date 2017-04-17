# test coverage for  [chai-as-promised (v6.0.0)](https://github.com/domenic/chai-as-promised#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-chai-as-promised.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-chai-as-promised) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-chai-as-promised.svg)](https://travis-ci.org/npmtest/node-npmtest-chai-as-promised)
#### Extends Chai with assertions about promises.

[![NPM](https://nodei.co/npm/chai-as-promised.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chai-as-promised)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-chai-as-promised/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-chai-as-promised/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-chai-as-promised/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-chai-as-promised/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-chai-as-promised/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-chai-as-promised/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-chai-as-promised/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-chai-as-promised/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-chai-as-promised/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-chai-as-promised/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-chai-as-promised/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-chai-as-promised/build/test-report.html](https://npmtest.github.io/node-npmtest-chai-as-promised/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-chai-as-promised/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-chai-as-promised/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-chai-as-promised/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chai-as-promised/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chai-as-promised/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chai-as-promised/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-chai-as-promised/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-chai-as-promised/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Domenic Denicola",
        "url": "https://domenic.me"
    },
    "bugs": {
        "url": "https://github.com/domenic/chai-as-promised/issues"
    },
    "dependencies": {
        "check-error": "^1.0.2"
    },
    "description": "Extends Chai with assertions about promises.",
    "devDependencies": {
        "chai": "^3.0.0",
        "coffee-script": "1.10.0",
        "ecstatic": "^1.3.1",
        "glob": "^6.0.1",
        "istanbul": "0.4.1",
        "jshint": "^2.8.0",
        "mocha": "^2.3.4",
        "opener": "^1.4.1",
        "q": "^1.4.1",
        "underscore": "1.8.3"
    },
    "directories": {},
    "dist": {
        "shasum": "1a02a433a6f24dafac63b9c96fa1684db1aa8da6",
        "tarball": "https://registry.npmjs.org/chai-as-promised/-/chai-as-promised-6.0.0.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "b2cfbdc71360dad1faaa29f64bcc8ba54819084e",
    "homepage": "https://github.com/domenic/chai-as-promised#readme",
    "keywords": [
        "chai",
        "chai-plugin",
        "browser",
        "async",
        "testing",
        "assertions",
        "promises",
        "promises-aplus"
    ],
    "license": "WTFPL",
    "main": "./lib/chai-as-promised.js",
    "maintainers": [
        {
            "name": "domenic"
        }
    ],
    "name": "chai-as-promised",
    "optionalDependencies": {},
    "peerDependencies": {
        "chai": ">= 2.1.2 < 4"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/domenic/chai-as-promised.git"
    },
    "scripts": {
        "cover": "istanbul cover node_modules/mocha/bin/_mocha && opener ./coverage/lcov-report/lib/chai-as-promised.js.html",
        "lint": "jshint ./lib",
        "test": "npm run test-plugin && npm run test-intercompatibility",
        "test-intercompatibility": "mocha test-intercompatibility --opts test-intercompatibility/mocha.opts",
        "test-plugin": "mocha"
    },
    "version": "6.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
