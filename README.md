# test coverage for  [ngrok (v2.2.6)](https://github.com/bubenshchykov/ngrok#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ngrok.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ngrok) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ngrok.svg)](https://travis-ci.org/npmtest/node-npmtest-ngrok)
#### node wrapper for ngrok

[![NPM](https://nodei.co/npm/ngrok.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ngrok)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ngrok/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ngrok/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ngrok/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ngrok/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ngrok/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ngrok/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ngrok/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ngrok/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ngrok/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ngrok/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ngrok/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ngrok/build/test-report.html](https://npmtest.github.io/node-npmtest-ngrok/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ngrok/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ngrok/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ngrok/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ngrok/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ngrok/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ngrok/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ngrok/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ngrok/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "bubenshchykov"
    },
    "bin": {
        "ngrok": "./bin/ngrok"
    },
    "bugs": {
        "url": "https://github.com/bubenshchykov/ngrok/issues"
    },
    "dependencies": {
        "async": "^0.9.0",
        "decompress-zip": "^0.3.0",
        "lock": "^0.1.2",
        "request": "^2.55.0",
        "uuid": "^3.0.0"
    },
    "description": "node wrapper for ngrok",
    "devDependencies": {
        "chai": "~1.8.1",
        "homedir": "^0.6.0",
        "mocha": "~1.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "404cb8ef7e11dcd399e17b3c76c5dc56aa79849a",
        "tarball": "https://registry.npmjs.org/ngrok/-/ngrok-2.2.6.tgz"
    },
    "files": [
        "index.js",
        "postinstall.js",
        "bin/ngrok"
    ],
    "gitHead": "607bdcbbda05d290e5095510392ff89d09706cae",
    "homepage": "https://github.com/bubenshchykov/ngrok#readme",
    "keywords": [
        "ngrok",
        "localhost",
        "tunneling",
        "localtunnel",
        "webhook"
    ],
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bubenshchykov"
        }
    ],
    "name": "ngrok",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/bubenshchykov/ngrok.git"
    },
    "scripts": {
        "postinstall": "node ./postinstall.js",
        "postupdate": "node ./postinstall.js",
        "test": "node ./node_modules/mocha/bin/_mocha"
    },
    "version": "2.2.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
