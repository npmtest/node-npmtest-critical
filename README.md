# npmtest-critical

#### basic test coverage for  [critical (v0.8.4)](https://github.com/addyosmani/critical#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-critical.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-critical) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-critical.svg)](https://travis-ci.org/npmtest/node-npmtest-critical)

#### Extract & Inline Critical-path CSS from HTML

[![NPM](https://nodei.co/npm/critical.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/critical)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-critical/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-critical/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-critical/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-critical/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-critical/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-critical/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-critical/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-critical/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-critical/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-critical/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-critical/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-critical/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-critical/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-critical/build/test-report.html](https://npmtest.github.io/node-npmtest-critical/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-critical/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-critical/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-critical/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-critical/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-critical/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-critical/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-critical/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-critical/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Addy Osmani"
    },
    "bin": {
        "critical": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/addyosmani/critical/issues"
    },
    "dependencies": {
        "bluebird": "^3.4.7",
        "chalk": "^1.1.3",
        "cheerio": "^0.22.0",
        "clean-css": "^4.0.6",
        "cli": "^1.0.1",
        "debug": "^2.6.1",
        "filter-css": "^0.1.2",
        "finalhandler": "^0.5.1",
        "fs-extra": "^2.0.0",
        "get-port": "^2.1.0",
        "get-stdin": "^5.0.1",
        "gulp-util": "^3.0.8",
        "imageinliner": "^0.2.4",
        "indent-string": "^3.1.0",
        "inline-critical": "^2.4.0",
        "lodash": "^4.17.4",
        "meow": "^3.7.0",
        "mime-types": "^2.1.14",
        "oust": "^0.3.0",
        "parseurl": "^1.3.1",
        "penthouse": "^0.10.9",
        "postcss": "^5.2.12",
        "postcss-image-inliner": "^1.0.4",
        "request": "^2.79.0",
        "serve-static": "^1.11.2",
        "slash": "^1.0.0",
        "tempfile": "^1.1.1",
        "through2": "^2.0.3",
        "tmp": "^0.0.31",
        "vinyl": "^2.0.1"
    },
    "description": "Extract & Inline Critical-path CSS from HTML",
    "devDependencies": {
        "async": "^2.1.4",
        "chai": "^3.5.0",
        "connect": "^3.5.0",
        "mocha": "^3.2.0",
        "mockery": "^2.0.0",
        "normalize-newline": "^3.0.0",
        "read-package-json": "^2.0.4",
        "stream-array": "^1.1.2",
        "stream-assert": "^2.0.3",
        "vinyl-source-stream": "^1.1.0",
        "xo": "^0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "beb716afa221a84c4ed216719c18e25a8ac8a3c2",
        "tarball": "https://registry.npmjs.org/critical/-/critical-0.8.4.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "files": [
        "cli.js",
        "index.js",
        "lib"
    ],
    "gitHead": "24465c459830e06af4a4fd593c0c287ee21c197c",
    "homepage": "https://github.com/addyosmani/critical#readme",
    "keywords": [
        "critical",
        "path",
        "css",
        "optimization"
    ],
    "license": "Apache-2.0",
    "maintainers": [
        {
            "name": "addyosmani"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "bezoerb"
        }
    ],
    "name": "critical",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/addyosmani/critical.git"
    },
    "scripts": {
        "test": "xo && mocha test/*.js --timeout 100000"
    },
    "version": "0.8.4",
    "xo": {
        "space": 4
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
