# test coverage for  [yauzl (v2.7.0)](https://github.com/thejoshwolfe/yauzl)  [![npm package](https://img.shields.io/npm/v/npmtest-yauzl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yauzl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yauzl.svg)](https://travis-ci.org/npmtest/node-npmtest-yauzl)
#### yet another unzip library for node

[![NPM](https://nodei.co/npm/yauzl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yauzl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yauzl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yauzl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yauzl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yauzl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yauzl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yauzl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yauzl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yauzl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yauzl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yauzl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yauzl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yauzl/build/test-report.html](https://npmtest.github.io/node-npmtest-yauzl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yauzl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yauzl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yauzl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yauzl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yauzl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yauzl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yauzl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yauzl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Josh Wolfe"
    },
    "bugs": {
        "url": "https://github.com/thejoshwolfe/yauzl/issues"
    },
    "dependencies": {
        "buffer-crc32": "~0.2.3",
        "fd-slicer": "~1.0.1"
    },
    "description": "yet another unzip library for node",
    "devDependencies": {
        "bl": "~1.0.0",
        "istanbul": "~0.3.4",
        "pend": "~1.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e21d847868b496fc29eaec23ee87fdd33e9b2bce",
        "tarball": "https://registry.npmjs.org/yauzl/-/yauzl-2.7.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "1f5cb3dc6f4e9d4df06e96c665af52e576616cc3",
    "homepage": "https://github.com/thejoshwolfe/yauzl",
    "keywords": [
        "unzip",
        "zip",
        "stream",
        "archive",
        "file"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "thejoshwolfe"
        },
        {
            "name": "superjoe"
        }
    ],
    "name": "yauzl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/thejoshwolfe/yauzl.git"
    },
    "scripts": {
        "test": "node test/test.js",
        "test-cov": "istanbul cover test/test.js",
        "test-travis": "istanbul cover --report lcovonly test/test.js"
    },
    "version": "2.7.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
