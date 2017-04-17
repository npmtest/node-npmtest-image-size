# test coverage for  [image-size (v0.5.1)](https://github.com/image-size/image-size#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-image-size.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-image-size) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-image-size.svg)](https://travis-ci.org/npmtest/node-npmtest-image-size)
#### get dimensions of any image file

[![NPM](https://nodei.co/npm/image-size.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/image-size)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-image-size/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-image-size/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-image-size/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-image-size/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-image-size/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-image-size/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-image-size/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-image-size/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-image-size/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-image-size/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-image-size/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-image-size/build/test-report.html](https://npmtest.github.io/node-npmtest-image-size/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-image-size/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-image-size/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-image-size/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-image-size/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-image-size/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-image-size/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-image-size/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-image-size/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "netroy",
        "url": "http://netroy.in/"
    },
    "bin": {
        "image-size": "bin/image-size.js"
    },
    "bugs": {
        "url": "https://github.com/image-size/image-size/issues"
    },
    "dependencies": {},
    "description": "get dimensions of any image file",
    "devDependencies": {
        "escomplex-js": "^1.2.0",
        "expect.js": "^0.3.1",
        "glob": "^7.1.1",
        "istanbul": "^0.4.0",
        "jshint": "^2.8.0",
        "mocha": "^3.2.0",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "28eea8548a4b1443480ddddc1e083ae54652439f",
        "tarball": "https://registry.npmjs.org/image-size/-/image-size-0.5.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "bin",
        "lib"
    ],
    "gitHead": "05fd80685ea70b2b7a27e76b16bc614f0949b4f4",
    "homepage": "https://github.com/image-size/image-size#readme",
    "keywords": [
        "image",
        "size",
        "dimensions",
        "resolution",
        "width",
        "height",
        "png",
        "jpeg",
        "bmp",
        "gif",
        "psd",
        "tiff",
        "webp",
        "svg"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "netroy"
        },
        {
            "name": "shinnn"
        },
        {
            "name": "zeke"
        }
    ],
    "name": "image-size",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/image-size/image-size.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha specs",
        "pretest": "jshint",
        "test": "mocha specs"
    },
    "version": "0.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
