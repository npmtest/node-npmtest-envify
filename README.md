# npmtest-envify

#### test coverage for  [envify (v4.0.0)](https://github.com/hughsk/envify#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-envify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-envify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-envify.svg)](https://travis-ci.org/npmtest/node-npmtest-envify)

#### Selectively replace Node-style environment variables with plain strings.

[![NPM](https://nodei.co/npm/envify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/envify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-envify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-envify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-envify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-envify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-envify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-envify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-envify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-envify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-envify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-envify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-envify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-envify/build/test-report.html](https://npmtest.github.io/node-npmtest-envify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-envify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-envify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-envify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-envify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-envify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-envify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-envify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-envify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hugh Kennedy",
        "url": "http://hughskennedy.com/"
    },
    "bin": {
        "envify": "bin/envify"
    },
    "bugs": {
        "url": "https://github.com/hughsk/envify/issues"
    },
    "dependencies": {
        "esprima": "~3.1.0",
        "through": "~2.3.4"
    },
    "description": "Selectively replace Node-style environment variables with plain strings.",
    "devDependencies": {
        "tap-spec": "^4.1.1",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f791343e3d11cc29cce41150300a8af61c66cab0",
        "tarball": "https://registry.npmjs.org/envify/-/envify-4.0.0.tgz"
    },
    "gitHead": "ae5d17b4eb5ace6d665161702a891bd36094d266",
    "homepage": "https://github.com/hughsk/envify#readme",
    "keywords": [
        "environment",
        "variables",
        "browserify",
        "browserify-transform",
        "transform",
        "source",
        "configuration"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "hughsk"
        },
        {
            "name": "yoshuawuyts"
        },
        {
            "name": "zertosh"
        }
    ],
    "name": "envify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hughsk/envify.git"
    },
    "scripts": {
        "test": "node test.js | tap-spec"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
