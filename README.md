# npmtest-websocket

#### basic test coverage for  [websocket (v1.0.24)](https://github.com/theturtle32/WebSocket-Node)  [![npm package](https://img.shields.io/npm/v/npmtest-websocket.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-websocket) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-websocket.svg)](https://travis-ci.org/npmtest/node-npmtest-websocket)

#### Websocket Client & Server Library implementing the WebSocket protocol as specified in RFC 6455.

[![NPM](https://nodei.co/npm/websocket.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/websocket)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-websocket/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-websocket/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-websocket/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-websocket/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-websocket/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-websocket/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-websocket/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-websocket/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-websocket/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-websocket/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-websocket/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-websocket/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-websocket/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-websocket/build/test-report.html](https://npmtest.github.io/node-npmtest-websocket/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-websocket/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-websocket/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-websocket/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-websocket/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-websocket/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-websocket/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-websocket/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-websocket/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian McKelvey",
        "url": "https://www.worlize.com/"
    },
    "browser": "lib/browser.js",
    "bugs": {
        "url": "https://github.com/theturtle32/WebSocket-Node/issues"
    },
    "config": {
        "verbose": false
    },
    "contributors": [
        {
            "name": "Iñaki Baz Castillo",
            "url": "http://dev.sipdoc.net"
        }
    ],
    "dependencies": {
        "debug": "^2.2.0",
        "nan": "^2.3.3",
        "typedarray-to-buffer": "^3.1.2",
        "yaeti": "^0.0.6"
    },
    "description": "Websocket Client & Server Library implementing the WebSocket protocol as specified in RFC 6455.",
    "devDependencies": {
        "buffer-equal": "^1.0.0",
        "faucet": "^0.0.1",
        "gulp": "git+https://github.com/gulpjs/gulp.git#4.0",
        "gulp-jshint": "^2.0.4",
        "jshint": "^2.0.0",
        "jshint-stylish": "^2.2.1",
        "tape": "^4.0.1"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "74903e75f2545b6b2e1de1425bc1c905917a1890",
        "tarball": "https://registry.npmjs.org/websocket/-/websocket-1.0.24.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "0e15f9445953927c39ce84a232cb7dd6e3adf12e",
    "homepage": "https://github.com/theturtle32/WebSocket-Node",
    "keywords": [
        "websocket",
        "websockets",
        "socket",
        "networking",
        "comet",
        "push",
        "RFC-6455",
        "realtime",
        "server",
        "client"
    ],
    "license": "Apache-2.0",
    "main": "index",
    "maintainers": [
        {
            "name": "theturtle32"
        }
    ],
    "name": "websocket",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/theturtle32/WebSocket-Node.git"
    },
    "scripts": {
        "gulp": "gulp",
        "install": "(node-gyp rebuild 2> builderror.log) || (exit 0)",
        "test": "faucet test/unit"
    },
    "version": "1.0.24",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
