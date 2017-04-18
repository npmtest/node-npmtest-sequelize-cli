# npmtest-sequelize-cli

#### test coverage for  [sequelize-cli (v2.7.0)](https://github.com/sequelize/cli)  [![npm package](https://img.shields.io/npm/v/npmtest-sequelize-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sequelize-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sequelize-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-sequelize-cli)

#### The Sequelize CLI

[![NPM](https://nodei.co/npm/sequelize-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sequelize-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sequelize-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sequelize-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sequelize-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sequelize-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sequelize-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sequelize-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sequelize-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sequelize-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sequelize-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sequelize-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sequelize-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sequelize-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-sequelize-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sequelize-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sequelize-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sequelize-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sequelize-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sequelize-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sequelize-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sequelize-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sequelize-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sascha Depold"
    },
    "bin": {
        "sequelize": "bin/sequelize"
    },
    "bugs": {
        "url": "https://github.com/sequelize/cli/issues"
    },
    "dependencies": {
        "bluebird": "^3.5.0",
        "cli-color": "~1.2.0",
        "findup-sync": "^0.4.0",
        "fs-extra": "^2.0.0",
        "gulp": "^3.9.1",
        "gulp-help": "~1.6.1",
        "js-beautify": "^1.6.11",
        "lodash": "^4.17.4",
        "moment": "^2.17.1",
        "resolve": "^1.3.2",
        "umzug": "^1.11.0",
        "yargs": "^7.0.1"
    },
    "description": "The Sequelize CLI",
    "devDependencies": {
        "coffee-script": "^1.12.4",
        "expect.js": "~0.3.1",
        "gulp-jscs": "^4.0.0",
        "gulp-jshint": "^2.0.4",
        "gulp-jshint-instafail": "^1.0.0",
        "gulp-mocha": "^4.1.0",
        "js2coffee": "^2.2.0",
        "jshint": "^2.9.4",
        "jshint-stylish": "^2.2.0",
        "mocha": "^3.2.0",
        "mysql": "^2.13.0",
        "nodeify": "^1.0.1",
        "pg": "^6.1.3",
        "pg-hstore": "^2.3.2",
        "run-sequence": "^1.2.2",
        "sequelize": "^3.30.2",
        "sqlite3": "^3.1.8",
        "through2": "^2.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "122c26bf46609001fbc158404529f795f3950ea2",
        "tarball": "https://registry.npmjs.org/sequelize-cli/-/sequelize-cli-2.7.0.tgz"
    },
    "gitHead": "c43da8c4204b75f58c9114436568cb426c403d05",
    "homepage": "https://github.com/sequelize/cli",
    "keywords": [
        "sequelize",
        "cli"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "americas"
        },
        {
            "name": "sdepold"
        },
        {
            "name": "sushantdhiman"
        }
    ],
    "name": "sequelize-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/sequelize/cli.git"
    },
    "scripts": {
        "test": "gulp"
    },
    "version": "2.7.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
