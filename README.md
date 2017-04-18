# npmtest-tsify

#### test coverage for  [tsify (v3.0.1)](https://github.com/TypeStrong/tsify)  [![npm package](https://img.shields.io/npm/v/npmtest-tsify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tsify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tsify.svg)](https://travis-ci.org/npmtest/node-npmtest-tsify)

#### Browserify plugin for compiling Typescript

[![NPM](https://nodei.co/npm/tsify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tsify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tsify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tsify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tsify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tsify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tsify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tsify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tsify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tsify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tsify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tsify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tsify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tsify/build/test-report.html](https://npmtest.github.io/node-npmtest-tsify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tsify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tsify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tsify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tsify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tsify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tsify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tsify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tsify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Greg Smith"
    },
    "bugs": {
        "url": "https://github.com/TypeStrong/tsify/issues"
    },
    "dependencies": {
        "convert-source-map": "^1.1.0",
        "fs.realpath": "^1.0.0",
        "object-assign": "^4.1.0",
        "semver": "^5.1.0",
        "through2": "^2.0.0",
        "tsconfig": "^5.0.3"
    },
    "description": "Browserify plugin for compiling Typescript",
    "devDependencies": {
        "babel-preset-react": "^6.5.0",
        "babelify": "^7.2.0",
        "browserify": "^13.0.0",
        "eslint": "^3.3.1",
        "event-stream": "^3.3.1",
        "fs-extra": "^0.30.0",
        "node-foo": "^0.2.3",
        "source-map": "^0.5.3",
        "string-to-stream": "^1.1.0",
        "tape": "^4.0.0",
        "test-peer-range": "^1.0.1",
        "typescript": "~2.0.3",
        "watchify": "^3.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "23509ff3b4e7110ca9656f6c27ca13ec856056f6",
        "tarball": "https://registry.npmjs.org/tsify/-/tsify-3.0.1.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "74d77849f669f1db5012a423d9e5bf6407ea6a6d",
    "homepage": "https://github.com/TypeStrong/tsify",
    "keywords": [
        "browserify",
        "browserify-plugin",
        "typescript"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "basarat"
        },
        {
            "name": "cartant"
        },
        {
            "name": "smrq"
        }
    ],
    "name": "tsify",
    "optionalDependencies": {},
    "peerDependencies": {
        "browserify": ">= 10.x",
        "typescript": ">= 2.x"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/TypeStrong/tsify.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "test-peer-range browserify",
        "test-main": "node test/test.js"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
