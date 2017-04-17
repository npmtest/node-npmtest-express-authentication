# test coverage for  [express-authentication (v0.3.2)](https://github.com/izaakschroeder/express-authentication)  [![npm package](https://img.shields.io/npm/v/npmtest-express-authentication.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-authentication) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-authentication.svg)](https://travis-ci.org/npmtest/node-npmtest-express-authentication)
#### Unopinionated authentication middleware for express.

[![NPM](https://nodei.co/npm/express-authentication.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-authentication)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-authentication/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-authentication/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-authentication/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-authentication/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-authentication/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-authentication/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-authentication/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-authentication/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-authentication/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-authentication/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-authentication/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-authentication/build/test-report.html](https://npmtest.github.io/node-npmtest-express-authentication/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-authentication/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-authentication/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-authentication/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-authentication/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-authentication/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-authentication/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-authentication/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-authentication/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Izaak Schroeder"
    },
    "bugs": {
        "url": "https://github.com/izaakschroeder/express-authentication/issues"
    },
    "dependencies": {
        "express-context": "^0.7.1",
        "lodash": "^3.6.0"
    },
    "description": "Unopinionated authentication middleware for express.",
    "devDependencies": {
        "chai": "*",
        "chai-things": "*",
        "eslint": "*",
        "eslint-plugin-nodeca": "*",
        "express": "^4.10.2",
        "istanbul": "*",
        "mocha": "*",
        "sinon": "*",
        "sinon-chai": "*",
        "supertest": "^0.15.0",
        "supertest-chai": "^0.0.8"
    },
    "directories": {},
    "dist": {
        "shasum": "b824f4b558510a59bfe324cda7c4f69e19e4756d",
        "tarball": "https://registry.npmjs.org/express-authentication/-/express-authentication-0.3.2.tgz"
    },
    "gitHead": "6190cf4003480fc45337fd8c2cf73a5b619f60bb",
    "homepage": "https://github.com/izaakschroeder/express-authentication",
    "keywords": [
        "authentication",
        "express"
    ],
    "license": "CC0-1.0",
    "main": "lib/authentication.js",
    "maintainers": [
        {
            "name": "izaakschroeder"
        }
    ],
    "name": "express-authentication",
    "optionalDependencies": {},
    "peerDependencies": {
        "express": "^4.10.2"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/izaakschroeder/express-authentication.git"
    },
    "scripts": {
        "coverage": "istanbul check-coverage --statement 100 --branch 100 --function 100",
        "lint": "eslint --ignore-path .gitignore .",
        "spec": "NODE_PATH=lib NODE_ENV=test istanbul cover node_modules/.bin/_mocha -- --sort --recursive -r test/helpers/chai -r test/helpers/sinon -R spec test/spec",
        "test": "npm run lint && npm run spec && npm run coverage"
    },
    "version": "0.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
