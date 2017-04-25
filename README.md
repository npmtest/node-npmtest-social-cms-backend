# npmtest-social-cms-backend

#### basic test coverage for  [social-cms-backend (v0.7.2)](https://github.com/dai-shi/social-cms-backend#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-social-cms-backend.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-social-cms-backend) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-social-cms-backend.svg)](https://travis-ci.org/npmtest/node-npmtest-social-cms-backend)

#### Express middleware to provide schema-less REST APIs for creating a social networking website primarily using angular.js. It comes with built-in authentication, authorization and notification features.

[![NPM](https://nodei.co/npm/social-cms-backend.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/social-cms-backend)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-social-cms-backend/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-social-cms-backend/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-social-cms-backend/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-social-cms-backend/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-social-cms-backend/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-social-cms-backend/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-social-cms-backend/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-social-cms-backend/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-social-cms-backend/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-social-cms-backend/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-social-cms-backend/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-social-cms-backend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-social-cms-backend/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-social-cms-backend/build/test-report.html](https://npmtest.github.io/node-npmtest-social-cms-backend/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-social-cms-backend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-social-cms-backend/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-social-cms-backend/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-social-cms-backend/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-social-cms-backend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-social-cms-backend/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-social-cms-backend/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-social-cms-backend/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daishi Kato"
    },
    "bugs": {
        "url": "https://github.com/dai-shi/social-cms-backend/issues"
    },
    "contributors": [
        {
            "name": "Shunsuke Watanabe"
        },
        {
            "name": "Teruhisa Yamamoto"
        },
        {
            "name": "Naoto Satoh"
        }
    ],
    "dependencies": {
        "async": "^1.5.2",
        "body-parser": "^1.15.2",
        "breeze-mongodb": "0.0.6",
        "cookie-parser": "^1.4.3",
        "express-session": "^1.13.0",
        "fb": "^1.1.1",
        "mongodb": "^1.4.40",
        "passport": "^0.3.2",
        "passport-facebook": "^2.1.1",
        "passport-http": "^0.3.0",
        "passport-local": "^1.0.0",
        "passport-twitter": "^1.0.4",
        "underscore": "^1.8.3"
    },
    "description": "Express middleware to provide schema-less REST APIs for creating a social networking website primarily using angular.js. It comes with built-in authentication, authorization and notification features.",
    "devDependencies": {
        "eslint": "^2.12.0",
        "express": "^4.14.0",
        "jsdom": "^9.2.1",
        "mocha": "~2.0.1",
        "request": "https://github.com/mikeal/request/archive/882b01bae5.tar.gz",
        "socket.io": "^1.4.6",
        "socket.io-client": "^1.4.6"
    },
    "directories": {},
    "dist": {
        "shasum": "ca108ebac21c19ba0cc82b48061b8486523f62f8",
        "tarball": "https://registry.npmjs.org/social-cms-backend/-/social-cms-backend-0.7.2.tgz"
    },
    "gitHead": "5fa0c0d2b58d9f27b671933ff6e6ae7af99ee8b8",
    "homepage": "https://github.com/dai-shi/social-cms-backend#readme",
    "keywords": [
        "express",
        "social",
        "cms",
        "rest",
        "angular"
    ],
    "license": "BSD-2-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "daishi"
        }
    ],
    "name": "social-cms-backend",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dai-shi/social-cms-backend.git"
    },
    "scripts": {
        "eslint": "eslint lib",
        "mocha": "mocha -t 15000",
        "test": "npm run eslint && npm run mocha"
    },
    "version": "0.7.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
