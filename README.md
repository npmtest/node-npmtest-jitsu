# npmtest-jitsu

#### basic test coverage for  [jitsu (v0.15.0)](https://github.com/nodejitsu/jitsu)  [![npm package](https://img.shields.io/npm/v/npmtest-jitsu.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jitsu) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jitsu.svg)](https://travis-ci.org/npmtest/node-npmtest-jitsu)

#### Flawless command line deployment of Node.js apps to the cloud

[![NPM](https://nodei.co/npm/jitsu.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jitsu)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jitsu/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jitsu/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jitsu/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jitsu/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jitsu/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jitsu/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jitsu/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jitsu/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jitsu/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jitsu/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jitsu/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jitsu/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jitsu/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jitsu/build/test-report.html](https://npmtest.github.io/node-npmtest-jitsu/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jitsu/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jitsu/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jitsu/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jitsu/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jitsu/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jitsu/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jitsu/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jitsu/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nodejitsu Inc."
    },
    "bin": {
        "jitsu": "./bin/jitsu"
    },
    "bugs": {
        "url": "https://github.com/nodejitsu/jitsu/issues"
    },
    "canihaz": {
        "npm": "1.3.15"
    },
    "dependencies": {
        "canihaz": "1.0.1",
        "colors": "0.6.2",
        "complete": "0.3.1",
        "dateformat": "1.0.8-1.2.3",
        "flatiron": "0.3.11",
        "flatiron-cli-config": "0.1.4",
        "flatiron-cli-users": "0.1.10",
        "fstream": "0.1.25",
        "fstream-npm": "0.1.6",
        "ladder": "0.0.1",
        "nodejitsu-api": "0.6.4",
        "opener": "1.4.x",
        "pkginfo": "0.3.0",
        "progress": "0.1.0",
        "request": "2.42.0",
        "require-analyzer": "0.5.0",
        "semver": "1.0.14",
        "spawn-command": "0.0.2",
        "tar": "0.1.18",
        "wizard": "0.0.1"
    },
    "description": "Flawless command line deployment of Node.js apps to the cloud",
    "devDependencies": {
        "nock": "0.46.x",
        "vows": "0.7.x"
    },
    "directories": {},
    "dist": {
        "shasum": "3af6b1f7a0a91680c059ca402feea6bbb0c4b0fb",
        "tarball": "https://registry.npmjs.org/jitsu/-/jitsu-0.15.0.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "gitHead": "b4a40605cb5b888ff13fc0b0f1cfa252ad0dd917",
    "homepage": "https://github.com/nodejitsu/jitsu",
    "keywords": [
        "cli",
        "nodejitsu",
        "cloud hosting",
        "platform-as-a-service",
        "deployment"
    ],
    "license": "MIT",
    "main": "./lib/jitsu",
    "maintainers": [
        {
            "name": "indexzero"
        },
        {
            "name": "julianduque"
        },
        {
            "name": "jcrugzz"
        },
        {
            "name": "swaagie"
        }
    ],
    "name": "jitsu",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/nodejitsu/jitsu.git"
    },
    "scripts": {
        "test": "vows test/commands/*-test.js test/lib/*-test.js --spec -i"
    },
    "version": "0.15.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
