# npmdoc-gulp-css-base64

#### api documentation for  [gulp-css-base64 (v1.3.4)](http://github.com/zckrs/gulp-css-base64)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-css-base64.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-css-base64) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-css-base64.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-css-base64)

#### Gulp's task for transform all resources found in a CSS into base64-encoded data URI strings

[![NPM](https://nodei.co/npm/gulp-css-base64.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-css-base64)

- [https://npmdoc.github.io/node-npmdoc-gulp-css-base64/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-css-base64/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-css-base64/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-css-base64/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-css-base64/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-css-base64/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-css-base64",
    "description": "Gulp's task for transform all resources found in a CSS into base64-encoded data URI strings",
    "version": "1.3.4",
    "homepage": "http://github.com/zckrs/gulp-css-base64",
    "repository": "zckrs/gulp-css-base64.git",
    "bugs": {
        "url": "http://github.com/zckrs/gulp-css-base64/issues"
    },
    "author": "Mehdy Dara <mdara@eleven-labs.com> (http://eleven-labs.com/)",
    "contributors": [
        "Mehdy Dara <mdara@eleven-labs.com> (http://eleven-labs.com/)",
        "Callum Jefferies <callum.jefferies@gmail.com> (http://callumj.uk/)"
    ],
    "files": [
        "src"
    ],
    "main": "./src/index.js",
    "keywords": [
        "gulpplugin",
        "css",
        "base64"
    ],
    "dependencies": {
        "async": "^1.5.0",
        "buffers": "^0.1.1",
        "chalk": "^1.1.1",
        "gulp-util": "^3.0.3",
        "mime": "^1.3.4",
        "request": "^2.67.0",
        "through2": "^2.0.0"
    },
    "devDependencies": {
        "coveralls": "^2.11.2",
        "eslint": "^1.10.3",
        "eslint-config-xo-space": "^0.7.0",
        "event-stream": "^3.3.2",
        "istanbul": "^0.4.1",
        "mocha": "^2.3.4",
        "mocha-lcov-reporter": "^1.0.0"
    },
    "scripts": {
        "test": "eslint . && mocha --reporter spec",
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "cover": "istanbul cover ./node_modules/mocha/bin/_mocha --report html -- test/*.js -R spec -t 5000"
    },
    "license": "MIT",
    "eslintConfig": {
        "extends": "xo-space",
        "env": {
            "mocha": true
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
