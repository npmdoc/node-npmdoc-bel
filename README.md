# npmdoc-bel

#### api documentation for  [bel (v4.6.0)](https://github.com/shama/bel)  [![npm package](https://img.shields.io/npm/v/npmdoc-bel.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bel) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bel.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bel)

#### A simple extension to native elements

[![NPM](https://nodei.co/npm/bel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bel)

- [https://npmdoc.github.io/node-npmdoc-bel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bel/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bel",
    "version": "4.6.0",
    "description": "A simple extension to native elements",
    "main": "index.js",
    "scripts": {
        "start": "wzrd test/index.js:bundle.js",
        "test": "standard && node test/server.js && browserify test/index.js | testron",
        "bench": "wzrd bench/index.js:bundle.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/shama/bel"
    },
    "keywords": [
        "virtual-dom",
        "element",
        "diffhtml"
    ],
    "files": [
        "index.js",
        "create.js"
    ],
    "author": "Kyle Robinson Young <kyle@dontkry.com> (http://dontkry.com)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/shama/bel/issues"
    },
    "homepage": "https://github.com/shama/bel",
    "dependencies": {
        "global": "^4.3.0",
        "hyperx": "^2.3.0",
        "on-load": "^3.2.0"
    },
    "devDependencies": {
        "browser-process-hrtime": "^0.1.2",
        "browserify": "^14.1.0",
        "electron-prebuilt": "^0.36.9",
        "morphdom": "^2.1.1",
        "standard": "^9.0.2",
        "tape": "^4.6.0",
        "testron": "^1.2.0",
        "wzrd": "^1.4.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
