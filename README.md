# npmdoc-atlasboard

#### api documentation for  [atlasboard (v1.1.3)](http://atlasboard.bitbucket.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-atlasboard.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-atlasboard) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-atlasboard.svg)](https://travis-ci.org/npmdoc/node-npmdoc-atlasboard)

#### AtlasBoard is dashboard/wallboard framework written all in JS

[![NPM](https://nodei.co/npm/atlasboard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/atlasboard)

- [https://npmdoc.github.io/node-npmdoc-atlasboard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-atlasboard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-atlasboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-atlasboard/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-atlasboard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-atlasboard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Atlassian"
    },
    "bin": {
        "atlasboard": "./lib/cli/cli.js"
    },
    "contributors": [
        {
            "name": "William Archinal"
        },
        {
            "name": "Christoph Kiehl"
        },
        {
            "name": "Alexander Dickson"
        },
        {
            "name": "Ivan Loire"
        },
        {
            "name": "Sam Day"
        }
    ],
    "dependencies": {
        "async": "^1.4.2",
        "body-parser": "^1.13.3",
        "cheerio": "^0.19.0",
        "colors": "^1.1.2",
        "compression": "^1.5.2",
        "connect-assets": "5.0.1",
        "css": "^2.2.1",
        "debug": "^2.2.0",
        "ejs": "2.3.3",
        "errorhandler": "^1.4.2",
        "express": "^4.12.3",
        "hardhat": "~0.0.7",
        "method-override": "2.3.5",
        "mkdirp": "~0.5.1",
        "moment": "^2.10.6",
        "morgan": "^1.6.1",
        "nib": "^1.1.0",
        "nock": "^2.10.0",
        "optimist": "~0.3.5",
        "pg": "4.3",
        "read-package-json": "^2.0.0",
        "request": "^2.61.0",
        "semver": "~2.0.11",
        "socket.io": "^1.3.6",
        "stylus": "0.52.0",
        "temp": "0.8.3",
        "tracer": "^0.8.0",
        "traverse": "^0.6.6",
        "underscore": "1.8.3",
        "xtend": "2.0.3"
    },
    "description": "AtlasBoard is dashboard/wallboard framework written all in JS",
    "devDependencies": {
        "bower": "^1.5.2",
        "bower-files": "^3.7.0",
        "expect.js": "0.1.2",
        "gulp": "^3.8.11",
        "gulp-concat": "^2.5.2",
        "gulp-eslint": "^1.0.0",
        "gulp-filter": "^2.0.2",
        "gulp-load-plugins": "^0.9.0",
        "gulp-mocha": "^2.1.3",
        "gulp-uglify": "^1.1.0",
        "gulp-watch": "^4.3.5",
        "mocha": "2.3.0",
        "proxyquire": "0.4.1",
        "rimraf": "2.1.4",
        "sinon": "1.16.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b13f5e43e62ef2eef2e8364d2808c703dfd85f95",
        "tarball": "https://registry.npmjs.org/atlasboard/-/atlasboard-1.1.3.tgz"
    },
    "engines": {
        "node": ">=0.12",
        "npm": "~2.0.0"
    },
    "gitHead": "edf788f90ad3930e52c9de7a82b74da2fa923793",
    "homepage": "http://atlasboard.bitbucket.org",
    "keywords": [
        "server",
        "dashboard"
    ],
    "license": "Apache-2.0",
    "main": "./lib/atlasboard.js",
    "maintainers": [
        {
            "name": "ckiehl"
        },
        {
            "name": "iloire"
        },
        {
            "name": "archinal"
        }
    ],
    "name": "atlasboard",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@bitbucket.org/atlassian/atlasboard.git"
    },
    "scripts": {
        "test": "mocha -b test --reporter list --ignore-leaks"
    },
    "version": "1.1.3",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "npm": "~2.0.0",
                "node": ">=0.12"
            },
            "pkgid": "atlasboard@1.1.3"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "npm": "~2.0.0",
                "node": ">=0.12"
            },
            "pkgid": "atlasboard@1.1.3"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
