# npmtest-babar

#### test coverage for  [babar (v0.1.0)](https://github.com/stephan83/babar#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-babar.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babar) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babar.svg)](https://travis-ci.org/npmtest/node-npmtest-babar)

#### CLI bar charts

[![NPM](https://nodei.co/npm/babar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babar)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babar/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babar/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babar/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babar/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babar/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babar/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babar/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babar/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babar/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babar/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babar/build/test-report.html](https://npmtest.github.io/node-npmtest-babar/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babar/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babar/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephan Florquin"
    },
    "bugs": {
        "url": "https://github.com/stephan83/babar/issues"
    },
    "dependencies": {
        "colors": "~0.6.2"
    },
    "description": "CLI bar charts",
    "devDependencies": {
        "coffee-script": "~1.6.3",
        "rimraf": "^2.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "b4fdb15e6ba8ed7a4096df66f23bf6171f60efc0",
        "tarball": "https://registry.npmjs.org/babar/-/babar-0.1.0.tgz"
    },
    "gitHead": "831e664860c9f80c71b51b7bffd59ff59defdd2c",
    "homepage": "https://github.com/stephan83/babar#readme",
    "keywords": [
        "cli",
        "bar",
        "charts",
        "graph",
        "ascii"
    ],
    "license": "MIT",
    "main": "lib/babar.js",
    "maintainers": [
        {
            "name": "stephan83"
        }
    ],
    "name": "babar",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stephan83/babar.git"
    },
    "scripts": {
        "build:lib": "coffee -o lib -c src/babar.coffee",
        "clean": "rimraf lib coverage",
        "dev": "coffee --watch -o lib/ -c src/babar.coffee",
        "postversion": "git push && git push --tags && npm run clean",
        "prepublish": "npm run clean && npm run build:lib",
        "preversion": "npm run clean",
        "test": "echo \"Error: no test specified\" && exit 1",
        "version": "npm run build:lib"
    },
    "version": "0.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
