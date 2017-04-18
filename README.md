# npmtest-ref

#### test coverage for  [ref (v1.3.4)](https://github.com/TooTallNate/ref#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ref.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ref) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ref.svg)](https://travis-ci.org/npmtest/node-npmtest-ref)

#### Turn Buffer instances into "pointers"

[![NPM](https://nodei.co/npm/ref.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ref)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ref/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ref/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ref/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ref/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ref/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ref/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ref/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ref/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ref/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ref/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ref/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ref/build/test-report.html](https://npmtest.github.io/node-npmtest-ref/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ref/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ref/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ref/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ref/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ref/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ref/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ref/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ref/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Rajlich",
        "url": "http://tootallnate.net"
    },
    "bugs": {
        "url": "https://github.com/TooTallNate/ref/issues"
    },
    "dependencies": {
        "bindings": "1",
        "debug": "2",
        "nan": "2"
    },
    "description": "Turn Buffer instances into \"pointers\"",
    "devDependencies": {
        "dox": "0.4.4",
        "highlight.js": "1",
        "jade": "^0.35.0",
        "marked": "^0.3.2",
        "mocha": "*",
        "weak": "1"
    },
    "directories": {},
    "dist": {
        "shasum": "724d2bf8ac85f8c8db194d3d85be6efe416bc1e5",
        "tarball": "https://registry.npmjs.org/ref/-/ref-1.3.4.tgz"
    },
    "gitHead": "bb9d570157b6e2c0d593b87cd5f69953dada78b9",
    "gypfile": true,
    "homepage": "https://github.com/TooTallNate/ref#readme",
    "keywords": [
        "native",
        "buffer",
        "extensions",
        "c++",
        "pointer",
        "reference",
        "dereference",
        "type",
        "int",
        "long",
        "float",
        "double",
        "byte",
        "64"
    ],
    "license": "MIT",
    "main": "./lib/ref.js",
    "maintainers": [
        {
            "name": "tootallnate"
        }
    ],
    "name": "ref",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/TooTallNate/ref.git"
    },
    "scripts": {
        "docs": "node docs/compile",
        "install": "node-gyp rebuild",
        "test": "mocha -gc --reporter spec --use_strict"
    },
    "version": "1.3.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
