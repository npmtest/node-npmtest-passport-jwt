# test coverage for  [passport-jwt (v2.2.1)](https://github.com/themikenicholson/passport-jwt)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-jwt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-jwt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-jwt.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-jwt)
#### Passport authentication strategy using JSON Web Tokens

[![NPM](https://nodei.co/npm/passport-jwt.png?downloads=true)](https://www.npmjs.com/package/passport-jwt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-jwt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-jwt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-jwt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-jwt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-jwt/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-jwt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-jwt/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-jwt/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-passport-jwt/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-jwt/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-passport-jwt%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-jwt/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-jwt/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-passport-jwt%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-jwt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-jwt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-jwt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike Nicholson"
    },
    "bugs": {
        "url": "https://github.com/themikenicholson/passport-jwt/issues"
    },
    "dependencies": {
        "jsonwebtoken": "^7.0.0",
        "passport-strategy": "^1.0.0"
    },
    "description": "Passport authentication strategy using JSON Web Tokens",
    "devDependencies": {
        "chai": "^3.0.0",
        "chai-passport-strategy": "^1.0.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.0.0",
        "sinon": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0e004c94071319d673d9d9bcfd1574a868011527",
        "tarball": "https://registry.npmjs.org/passport-jwt/-/passport-jwt-2.2.1.tgz"
    },
    "gitHead": "6ff2a4a63ff6e3475fc0fb28207221e9ca4d3d48",
    "homepage": "https://github.com/themikenicholson/passport-jwt",
    "keywords": [
        "Passport",
        "Strategy",
        "JSON",
        "Web",
        "Token",
        "JWT"
    ],
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "themikenicholson",
            "email": "themikenicholson@gmail.com"
        }
    ],
    "name": "passport-jwt",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/themikenicholson/passport-jwt.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --require test/bootstrap test/*test.js",
        "testcov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter spec --require test/bootstrap test/*test.js"
    },
    "version": "2.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
