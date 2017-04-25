# npmtest-runas

#### basic test coverage for  [runas (v3.1.1)](https://github.com/atom/node-runas#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-runas.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-runas) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-runas.svg)](https://travis-ci.org/npmtest/node-npmtest-runas)

#### Run command synchronously with administrator privilege.

[![NPM](https://nodei.co/npm/runas.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/runas)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-runas/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-runas/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-runas/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-runas/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-runas/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-runas/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-runas/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-runas/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-runas/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-runas/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-runas/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-runas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-runas/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-runas/build/test-report.html](https://npmtest.github.io/node-npmtest-runas/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-runas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-runas/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-runas/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-runas/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-runas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-runas/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-runas/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-runas/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/atom/node-runas/issues"
    },
    "dependencies": {
        "nan": "2.x"
    },
    "description": "Run command synchronously with administrator privilege.",
    "devDependencies": {
        "coffee-script": "~1.6.2",
        "grunt": "~0.4.1",
        "grunt-cli": "~0.1.7",
        "grunt-contrib-coffee": "~0.6.6",
        "grunt-shell": "~0.2.2",
        "jasmine-focused": "^1.0.5",
        "node-cpplint": "~0.1.5"
    },
    "directories": {},
    "dist": {
        "shasum": "52dd538db0e41745399535a347091ba45cc0eab0",
        "tarball": "https://registry.npmjs.org/runas/-/runas-3.1.1.tgz"
    },
    "gitHead": "dc0dcf3711ae265367b90d9ee02f77cf1c26bad8",
    "gypfile": true,
    "homepage": "https://github.com/atom/node-runas#readme",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/atom/node-runas/raw/master/LICENSE.md"
        }
    ],
    "main": "./lib/runas.js",
    "maintainers": [
        {
            "name": "zcbenz"
        },
        {
            "name": "kevinsawicki"
        },
        {
            "name": "nathansobo"
        },
        {
            "name": "benogle"
        }
    ],
    "name": "runas",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/atom/node-runas.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "prepublish": "grunt coffee",
        "test": "node node_modules/jasmine-focused/bin/jasmine-focused --captureExceptions --coffee spec"
    },
    "version": "3.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
