# npmtest-flatpickr

#### basic test coverage for  [flatpickr (v2.5.8)](https://chmln.github.io/flatpickr)  [![npm package](https://img.shields.io/npm/v/npmtest-flatpickr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-flatpickr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-flatpickr.svg)](https://travis-ci.org/npmtest/node-npmtest-flatpickr)

#### A lightweight, powerful javascript datetime picker

[![NPM](https://nodei.co/npm/flatpickr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/flatpickr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-flatpickr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-flatpickr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-flatpickr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-flatpickr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-flatpickr/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-flatpickr/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-flatpickr/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-flatpickr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-flatpickr/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-flatpickr/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-flatpickr/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-flatpickr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-flatpickr/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-flatpickr/build/test-report.html](https://npmtest.github.io/node-npmtest-flatpickr/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-flatpickr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-flatpickr/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-flatpickr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-flatpickr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-flatpickr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-flatpickr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-flatpickr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-flatpickr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gregory"
    },
    "browserslist": [
        "ie >= 9",
        "last 2 versions",
        "safari >= 7"
    ],
    "bugs": {
        "url": "https://github.com/chmln/flatpickr/issues"
    },
    "collective": {
        "type": "opencollective",
        "url": "https://opencollective.com/flatpickr",
        "logo": "https://opencollective.com/opencollective/logo.txt"
    },
    "dependencies": {},
    "description": "A lightweight, powerful javascript datetime picker",
    "devDependencies": {
        "autoprefixer-stylus": "^0.13.0",
        "babel-cli": "next",
        "babel-plugin-transform-object-assign": "next",
        "babel-plugin-transform-remove-strict-mode": "latest",
        "babel-preset-es2015": "next",
        "chokidar": "^1.6.1",
        "coveralls": "latest",
        "eslint": "latest",
        "glob": "^7.1.1",
        "http-server": "latest",
        "jest": "latest",
        "livereload": "latest",
        "ncp": "latest",
        "node-watch": "^0.5.2",
        "nodemon": "^1.11.0",
        "npm-run-all": "latest",
        "opn": "^4.0.2",
        "rtlcss": "latest",
        "semver": "latest",
        "stylus": "latest",
        "uglify-js": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "e9a0eb73c6e95573fcdcd378c8487e22902c3eac",
        "tarball": "https://registry.npmjs.org/flatpickr/-/flatpickr-2.5.8.tgz"
    },
    "gitHead": "f299bf3553eb7a6692588f5e1799a2b4e55af2b4",
    "homepage": "https://chmln.github.io/flatpickr",
    "keywords": [
        "javascript",
        "datetimepicker",
        "calendar",
        "date",
        "time",
        "picker",
        "lightweight"
    ],
    "license": "MIT",
    "main": "dist/flatpickr.js",
    "maintainers": [
        {
            "name": "chmln"
        }
    ],
    "name": "flatpickr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/chmln/flatpickr.git"
    },
    "scripts": {
        "build": "node build.js",
        "coveralls": "jest --coverage && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js",
        "release": "jest --bail --silent && ./release",
        "start": "nodemon --watch build.js build.js -- --dev",
        "test": "jest --bail"
    },
    "style": "dist/flatpickr.css",
    "version": "2.5.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
