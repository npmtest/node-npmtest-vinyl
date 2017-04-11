# test coverage for  [vinyl (v2.0.1)](https://github.com/gulpjs/vinyl#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-vinyl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vinyl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vinyl.svg)](https://travis-ci.org/npmtest/node-npmtest-vinyl)
#### Virtual file format.

[![NPM](https://nodei.co/npm/vinyl.png?downloads=true)](https://www.npmjs.com/package/vinyl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vinyl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vinyl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vinyl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vinyl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vinyl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vinyl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vinyl/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vinyl/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-vinyl/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-vinyl/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-vinyl%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vinyl/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vinyl/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-vinyl%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vinyl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vinyl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vinyl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gulp Team",
        "email": "team@gulpjs.com",
        "url": "http://gulpjs.com/"
    },
    "bugs": {
        "url": "https://github.com/gulpjs/vinyl/issues"
    },
    "contributors": [
        {
            "name": "Eric Schoffstall",
            "email": "yo@contra.io"
        },
        {
            "name": "Blaine Bublitz",
            "email": "blaine.bublitz@gmail.com"
        }
    ],
    "dependencies": {
        "clone": "^1.0.0",
        "clone-buffer": "^1.0.0",
        "clone-stats": "^1.0.0",
        "cloneable-readable": "^1.0.0",
        "is-stream": "^1.1.0",
        "remove-trailing-separator": "^1.0.1",
        "replace-ext": "^1.0.0"
    },
    "description": "Virtual file format.",
    "devDependencies": {
        "eslint": "^1.7.3",
        "eslint-config-gulp": "^2.0.0",
        "expect": "^1.20.2",
        "istanbul": "^0.4.3",
        "istanbul-coveralls": "^1.0.3",
        "jscs": "^2.3.5",
        "jscs-preset-gulp": "^1.0.0",
        "mississippi": "^1.2.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "1c3b4931e7ac4c1efee743f3b91a74c094407bb6",
        "tarball": "https://registry.npmjs.org/vinyl/-/vinyl-2.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "LICENSE",
        "index.js",
        "lib"
    ],
    "gitHead": "12d62daa7e43cb7f5699928a4cbb057d6aa9b251",
    "homepage": "https://github.com/gulpjs/vinyl#readme",
    "keywords": [
        "virtual",
        "filesystem",
        "file",
        "directory",
        "stat",
        "path"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "contra",
            "email": "contra@wearefractal.com"
        },
        {
            "name": "fractal",
            "email": "contact@wearefractal.com"
        },
        {
            "name": "phated",
            "email": "blaine.bublitz@gmail.com"
        }
    ],
    "name": "vinyl",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gulpjs/vinyl.git"
    },
    "scripts": {
        "cover": "istanbul cover _mocha --report lcovonly",
        "coveralls": "npm run cover && istanbul-coveralls",
        "lint": "eslint . && jscs index.js lib/ test/",
        "pretest": "npm run lint",
        "test": "mocha --async-only"
    },
    "version": "2.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
