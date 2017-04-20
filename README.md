# npmtest-electron-installer-squirrel-windows

#### basic test coverage for  [electron-installer-squirrel-windows (v1.3.0)](http://github.com/mongodb-js/electron-installer-squirrel-windows)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-installer-squirrel-windows.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-installer-squirrel-windows) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-installer-squirrel-windows.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-installer-squirrel-windows)

#### Generate Windows installers for Electron apps using Squirrel.

[![NPM](https://nodei.co/npm/electron-installer-squirrel-windows.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-installer-squirrel-windows)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-installer-squirrel-windows/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-installer-squirrel-windows/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-installer-squirrel-windows/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-installer-squirrel-windows/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-installer-squirrel-windows/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-installer-squirrel-windows/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-installer-squirrel-windows/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-installer-squirrel-windows",
    "version": "1.3.0",
    "description": "Generate Windows installers for Electron apps using Squirrel.",
    "author": "Lucas Hrabovsky <lucas@mongodb.com> (http://imlucas.com)",
    "homepage": "http://github.com/mongodb-js/electron-installer-squirrel-windows",
    "license": "Apache-2.0",
    "repository": {
        "type": "git",
        "url": "https://github.com/mongodb-js/electron-installer-squirrel-windows.git"
    },
    "scripts": {
        "ci": "mocha",
        "test": "mocha",
        "coverage": "./node_modules/istanbul/lib/cli.js cover _mocha",
        "check": "mongodb-js-precommit"
    },
    "precommit": [
        "check"
    ],
    "bin": {
        "electron-installer-squirrel-windows": "bin/electron-installer-squirrel-windows.js"
    },
    "check": {
        "ignore": [
            "coverage/**/*"
        ]
    },
    "dependencies": {
        "ampersand-model": "^6.0.2",
        "asar": "~0.9.1",
        "async": "^1.5.2",
        "debug": "^2.2.0",
        "fs-extra": "^0.26.5",
        "lodash.assign": "^4.0.1",
        "lodash.clone": "^4.0.2",
        "lodash.foreach": "^4.0.0",
        "lodash.template": "^4.0.1",
        "minimist": "^1.2.0",
        "temp": "^0.8.3",
        "titlecase": "^1.0.2"
    },
    "keywords": [
        "mongodb.js",
        "electron",
        "electron-installer",
        "squirrel",
        "squirrel.windows",
        "electron windows setup.exe"
    ],
    "devDependencies": {
        "electron-installer-fixture-windows": "^0.0.3",
        "eslint-config-mongodb-js": "^1.0.6",
        "istanbul": "^0.4.2",
        "mocha": "^2.4.4",
        "mongodb-js-precommit": "^0.2.8",
        "pre-commit": "^1.1.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
