# test coverage for  [string (v3.3.3)](http://stringjs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-string.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-string) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-string.svg)](https://travis-ci.org/npmtest/node-npmtest-string)
#### string contains methods that aren't included in the vanilla JavaScript string such as escaping html, decoding html entities, stripping tags, etc.

[![NPM](https://nodei.co/npm/string.png?downloads=true)](https://www.npmjs.com/package/string)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-string/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-string/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-string/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-string/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-string/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-string/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-string/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-string/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-string/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-string/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-string%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-string/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-string/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-string%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-string/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-string/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-string/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "JP Richardson",
        "email": "jprichardson@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/jprichardson/string.js/issues"
    },
    "dependencies": {},
    "description": "string contains methods that aren't included in the vanilla JavaScript string such as escaping html, decoding html entities, stripping tags, etc.",
    "devDependencies": {
        "gulp": "3.8.11",
        "gulp-browserify": "0.5.1",
        "gulp-mocha": "2.0.0",
        "gulp-rename": "1.2.0",
        "gulp-rimraf": "^0.1.1",
        "gulp-uglify": "1.1.0",
        "istanbul": "*",
        "mocha": "*",
        "mochify": "^2.9.0",
        "uglify-js": "1.3.x"
    },
    "directories": {},
    "dist": {
        "shasum": "5ea211cd92d228e184294990a6cc97b366a77cb0",
        "tarball": "https://registry.npmjs.org/string/-/string-3.3.3.tgz"
    },
    "gitHead": "21eb9f67a545d9320558b20876b1551e9f38e52f",
    "homepage": "http://stringjs.com",
    "keywords": [
        "string",
        "strings",
        "string.js",
        "stringjs",
        "S",
        "s",
        "csv",
        "html",
        "entities",
        "parse",
        "html",
        "tags",
        "strip",
        "trim",
        "encode",
        "decode",
        "escape",
        "unescape"
    ],
    "license": "MIT",
    "main": "lib/string",
    "maintainers": [
        {
            "name": "jprichardson",
            "email": "jprichardson@gmail.com"
        },
        {
            "name": "az7arul",
            "email": "az7arul@gmail.com"
        }
    ],
    "name": "string",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jprichardson/string.js.git"
    },
    "scripts": {
        "istanbul": "istanbul cover node_modules/.bin/_mocha test/string.test.js",
        "test": "gulp test"
    },
    "version": "3.3.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
