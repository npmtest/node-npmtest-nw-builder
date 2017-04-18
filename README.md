# npmtest-nw-builder

#### test coverage for  [nw-builder (v3.2.0)](https://github.com/mllrsohn/nw-builder)  [![npm package](https://img.shields.io/npm/v/npmtest-nw-builder.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nw-builder) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nw-builder.svg)](https://travis-ci.org/npmtest/node-npmtest-nw-builder)

#### nw-builder

[![NPM](https://nodei.co/npm/nw-builder.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nw-builder)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nw-builder/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nw-builder/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nw-builder/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nw-builder/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nw-builder/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nw-builder/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nw-builder/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nw-builder/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nw-builder/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nw-builder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nw-builder/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nw-builder/build/test-report.html](https://npmtest.github.io/node-npmtest-nw-builder/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nw-builder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nw-builder/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nw-builder/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nw-builder/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nw-builder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nw-builder/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nw-builder/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nw-builder/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Steffen Müller"
    },
    "bin": {
        "nwbuild": "./bin/nwbuild"
    },
    "bugs": {
        "url": "https://github.com/mllrsohn/nw-builder/issues"
    },
    "contributors": [
        {
            "name": "Adam Lynch"
        }
    ],
    "dependencies": {
        "archiver": "^1.3.0",
        "bluebird": "^3.4.0",
        "decompress-zip": "0.3.0",
        "deprecate": "~1.0.0",
        "graceful-fs-extra": "^2.0.0",
        "graceful-ncp": "^3.0.0",
        "inherits": "~2.0.1",
        "lodash": "~4.17.4",
        "optimist": "^0.6.1",
        "platform-overrides": "~1.0.1",
        "plist": "^2.0.1",
        "progress": "~1.1.7",
        "rcedit": "^0.7.0",
        "recursive-readdir-sync": "^1.0.6",
        "request": "~2.79.0",
        "rimraf": "^2.5.2",
        "semver": "^2.3.2",
        "simple-glob": "~0.1.0",
        "tar-fs": "^1.13.0",
        "temp": "~0.7.0",
        "update-notifier": "^1.0.2",
        "winresourcer": "^0.9.0"
    },
    "description": "nw-builder",
    "devDependencies": {
        "eol": "~0.6.0",
        "nock": "^9.0.5",
        "redtape": "~1.0.0",
        "tap-spec": "^4.1.1",
        "tape": "~4.6.2"
    },
    "directories": {},
    "dist": {
        "shasum": "cb45b89aed8c427661f097253b8ebc55d63afd39",
        "tarball": "https://registry.npmjs.org/nw-builder/-/nw-builder-3.2.0.tgz"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "gitHead": "a9ed78b49cea6c8019dd88c85403a46a4ddfdbb6",
    "homepage": "https://github.com/mllrsohn/nw-builder",
    "keywords": [
        "NW.js",
        "node-webkit",
        "desktop",
        "application"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "adam-lynch"
        }
    ],
    "name": "nw-builder",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mllrsohn/nw-builder.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "version": "3.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
