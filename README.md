# npmtest-gulp-cssimport

#### basic test coverage for  [gulp-cssimport (v5.0.0)](https://github.com/unlight/gulp-cssimport#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-cssimport.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-cssimport) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-cssimport.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-cssimport)

#### Parses a CSS file, finds imports, grabs the content of the linked file and replaces the import statement with it.

[![NPM](https://nodei.co/npm/gulp-cssimport.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-cssimport)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-cssimport/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gulp-cssimport/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-cssimport/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-cssimport/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-cssimport/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-cssimport/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-cssimport/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-cssimport/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-cssimport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-cssimport/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-cssimport/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/unlight/gulp-cssimport/issues"
    },
    "dependencies": {
        "collect-stream": "^1.0.0",
        "deep-extend": "^0.4.0",
        "gulp-util": "*",
        "http-https": "^1.0.0",
        "lodash.trim": "^4.4.0",
        "lookup-path": "^0.3.1",
        "magic-string": "0.15.2",
        "minimatch": "3.0.2",
        "pify": "^2.3.0",
        "through2": "^2.0.1",
        "vinyl-sourcemaps-apply": "^0.2.1"
    },
    "description": "Parses a CSS file, finds imports, grabs the content of the linked file and replaces the import statement with it.",
    "devDependencies": {
        "gulp": "3",
        "gulp-bump": "2.2.0",
        "gulp-eslint": "3.0.1",
        "gulp-load-plugins": "1.2.4",
        "gulp-sourcemaps": "*",
        "tape": "4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2d0502ed0d921561008a195ca842484a1742389f",
        "tarball": "https://registry.npmjs.org/gulp-cssimport/-/gulp-cssimport-5.0.0.tgz"
    },
    "gitHead": "5ad6c3270ecbb8e996effdf0c55d09c09b749805",
    "homepage": "https://github.com/unlight/gulp-cssimport#readme",
    "keywords": [
        "css",
        "gulpplugin",
        "import"
    ],
    "license": "Xnet",
    "main": "gulp-cssimport.js",
    "maintainers": [
        {
            "name": "iamthes"
        }
    ],
    "name": "gulp-cssimport",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/unlight/gulp-cssimport.git"
    },
    "scripts": {
        "test": "cd test && node index.js"
    },
    "version": "5.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
