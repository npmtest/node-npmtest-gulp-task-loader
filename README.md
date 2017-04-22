# npmtest-gulp-task-loader

#### basic test coverage for  [gulp-task-loader (v1.4.4)](https://github.com/hontas/gulp-task-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-task-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-task-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-task-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-task-loader)

#### Load gulp tasks from folder

[![NPM](https://nodei.co/npm/gulp-task-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-task-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-task-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-task-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-task-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-task-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-task-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-task-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pontus Lundin"
    },
    "bugs": {
        "url": "https://github.com/hontas/gulp-task-loader/issues"
    },
    "dependencies": {
        "object-assign": "^4.0.1"
    },
    "description": "Load gulp tasks from folder",
    "devDependencies": {
        "chai": "^3.5.0",
        "coffee-script": "^1.10.0",
        "eslint": "^2.7.0",
        "gulp": "^3.9.1",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "58ead58179e7adca261a28b96146b254ebb660e8",
        "tarball": "https://registry.npmjs.org/gulp-task-loader/-/gulp-task-loader-1.4.4.tgz"
    },
    "gitHead": "1e707b4d8f656c3932185a3f977e45f3b0f459f9",
    "homepage": "https://github.com/hontas/gulp-task-loader#readme",
    "keywords": [
        "gulp",
        "task",
        "loader"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "hontas"
        }
    ],
    "name": "gulp-task-loader",
    "optionalDependencies": {},
    "peerDependencies": {
        "gulp": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hontas/gulp-task-loader.git"
    },
    "scripts": {
        "major": "npm version major -m 'New major version %s' && npm publish",
        "minor": "npm version minor -m 'New minor version %s' && npm publish",
        "patch": "npm version patch -m 'New patch version %s' && npm publish",
        "postpublish": "git push --follow-tags",
        "tdd": "npm run test -- --watch --reporter nyan",
        "test": "eslint . && mocha --reporter dot"
    },
    "version": "1.4.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
