# npmtest-linux

#### basic test coverage for  [linux (v2.6.0)](https://github.com/maxogden/linux#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-linux.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-linux) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-linux.svg)](https://travis-ci.org/npmtest/node-npmtest-linux)

#### run linux

[![NPM](https://nodei.co/npm/linux.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/linux)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-linux/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-linux/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-linux/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-linux/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-linux/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-linux/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-linux/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-linux/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-linux/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-linux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-linux/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-linux/build/test-report.html](https://npmtest.github.io/node-npmtest-linux/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-linux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-linux/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-linux/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-linux/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-linux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-linux/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-linux/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-linux/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "linux",
    "version": "2.6.0",
    "description": "run linux",
    "main": "index.js",
    "bin": {
        "linux": "cli.js"
    },
    "scripts": {
        "postinstall": "node download.js",
        "test": "standard"
    },
    "author": "",
    "license": "ISC",
    "dependencies": {
        "cat-names": "^1.0.2",
        "daemonspawn": "^1.0.1",
        "keypair": "^1.0.0",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "node-forge": "^0.6.34",
        "nugget": "^1.5.4",
        "psjson": "^0.1.0"
    },
    "devDependencies": {
        "standard": "^5.2.2"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/maxogden/linux.git"
    },
    "bugs": {
        "url": "https://github.com/maxogden/linux/issues"
    },
    "homepage": "https://github.com/maxogden/linux#readme"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
