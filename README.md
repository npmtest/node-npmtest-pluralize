# npmtest-pluralize

#### basic test coverage for  [pluralize (v4.0.0)](https://github.com/blakeembrey/pluralize#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pluralize.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pluralize) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pluralize.svg)](https://travis-ci.org/npmtest/node-npmtest-pluralize)

#### Pluralize and singularize any word

[![NPM](https://nodei.co/npm/pluralize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pluralize)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pluralize/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pluralize/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pluralize/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pluralize/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pluralize/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-pluralize/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-pluralize/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pluralize/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pluralize/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pluralize/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pluralize/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pluralize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pluralize/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pluralize/build/test-report.html](https://npmtest.github.io/node-npmtest-pluralize/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pluralize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pluralize/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pluralize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pluralize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pluralize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pluralize/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pluralize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pluralize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Blake Embrey",
        "url": "http://blakeembrey.me"
    },
    "bugs": {
        "url": "https://github.com/blakeembrey/pluralize/issues"
    },
    "dependencies": {},
    "description": "Pluralize and singularize any word",
    "devDependencies": {
        "chai": "^3.2.0",
        "istanbul": "^0.3.0",
        "mocha": "^2.3.2",
        "semistandard": "^7.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "59b708c1c0190a2f692f1c7618c446b052fd1762",
        "tarball": "https://registry.npmjs.org/pluralize/-/pluralize-4.0.0.tgz"
    },
    "files": [
        "pluralize.js"
    ],
    "gitHead": "ce8fa7f7486d292195f4bd330e7376eeca0f3f1d",
    "homepage": "https://github.com/blakeembrey/pluralize#readme",
    "keywords": [
        "plural",
        "plurals",
        "pluralize",
        "singular",
        "singularize",
        "inflection"
    ],
    "license": "MIT",
    "main": "pluralize.js",
    "maintainers": [
        {
            "name": "blakeembrey"
        }
    ],
    "name": "pluralize",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/blakeembrey/pluralize.git"
    },
    "scripts": {
        "lint": "semistandard",
        "test": "npm run lint && npm run test-cov",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- -R spec --bail",
        "test-spec": "mocha -R spec --bail"
    },
    "version": "4.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
