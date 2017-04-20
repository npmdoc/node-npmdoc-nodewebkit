# npmdoc-nodewebkit

#### api documentation for  nodewebkit (v0.11.6)  [![npm package](https://img.shields.io/npm/v/npmdoc-nodewebkit.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nodewebkit) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nodewebkit.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nodewebkit)

#### A installer for node-webkit

[![NPM](https://nodei.co/npm/nodewebkit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodewebkit)

- [https://npmdoc.github.io/node-npmdoc-nodewebkit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodewebkit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodewebkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodewebkit/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nodewebkit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nodewebkit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nodewebkit",
    "version": "0.11.6",
    "description": "A installer for node-webkit",
    "repository": {
        "type": "git",
        "url": "git://github.com/shama/nodewebkit.git"
    },
    "main": "index.js",
    "bin": {
        "nodewebkit": "bin/nodewebkit"
    },
    "scripts": {
        "postinstall": "node scripts/install.js",
        "test": "node test/index.js"
    },
    "files": [
        "lib",
        "bin",
        "scripts",
        "index.js"
    ],
    "author": "Kyle Robinson Young",
    "license": "MIT",
    "dependencies": {
        "rimraf": "^2.2.2",
        "download": "^0.1.10",
        "multimeter": "^0.1.1",
        "yargs": "^1.2.1",
        "semver": "^2.3.1"
    },
    "devDependencies": {
        "request": "^2.30.0",
        "tape": "^2.12.3"
    },
    "keywords": [
        "node-webkit",
        "webkit",
        "installer",
        "desktop",
        "application"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
