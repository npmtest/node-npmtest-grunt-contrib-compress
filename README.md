# npmtest-grunt-contrib-compress

#### basic test coverage for  [grunt-contrib-compress (v1.4.1)](https://github.com/gruntjs/grunt-contrib-compress#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-contrib-compress.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-contrib-compress) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-contrib-compress.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-contrib-compress)

#### Compress files and folders

[![NPM](https://nodei.co/npm/grunt-contrib-compress.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-contrib-compress)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-contrib-compress/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-contrib-compress/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-contrib-compress/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-contrib-compress/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-contrib-compress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-contrib-compress/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-contrib-compress/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "appveyor_id": "tiwbi1smm1j8aa5j",
    "author": {
        "name": "Grunt Team",
        "url": "http://gruntjs.com/"
    },
    "bugs": {
        "url": "https://github.com/gruntjs/grunt-contrib-compress/issues"
    },
    "contributors": [
        {
            "name": "Chris Talkington",
            "url": "http://christalkington.com/"
        },
        {
            "name": "Tyler Kellen",
            "url": "http://goingslowly.com/"
        },
        {
            "name": "Kyle Robinson Young",
            "url": "http://twitter.com/shamakry"
        },
        {
            "name": "Dav Glass",
            "url": "http://blog.davglass.com/"
        }
    ],
    "dependencies": {
        "archiver": "^1.0.0",
        "chalk": "^1.1.1",
        "iltorb": "^1.0.13",
        "lodash": "^4.7.0",
        "pretty-bytes": "^3.0.1",
        "stream-buffers": "^2.1.0"
    },
    "description": "Compress files and folders",
    "devDependencies": {
        "grunt": "^1.0.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-internal": "^1.1.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "tar": "^2.2.1",
        "unzip": "^0.1.5"
    },
    "directories": {},
    "dist": {
        "shasum": "36212e9bbb41e9b41ff6fbe2fc77281c69ab02a0",
        "tarball": "https://registry.npmjs.org/grunt-contrib-compress/-/grunt-contrib-compress-1.4.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "tasks"
    ],
    "gitHead": "21a55fba21158d02aa004f0d47d904039bb1ee8f",
    "homepage": "https://github.com/gruntjs/grunt-contrib-compress#readme",
    "keywords": [
        "gruntplugin",
        "compress",
        "zip",
        "tar"
    ],
    "license": "MIT",
    "main": "tasks/compress.js",
    "maintainers": [
        {
            "name": "cowboy"
        },
        {
            "name": "jmeas"
        },
        {
            "name": "shama"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "tkellen"
        },
        {
            "name": "vladikoff"
        },
        {
            "name": "xhmikosr"
        }
    ],
    "name": "grunt-contrib-compress",
    "optionalDependencies": {
        "iltorb": "^1.0.13"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gruntjs/grunt-contrib-compress.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.4.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
