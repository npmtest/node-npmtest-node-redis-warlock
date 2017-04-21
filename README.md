# npmtest-node-redis-warlock

#### basic test coverage for  [node-redis-warlock (v0.2.0)](https://github.com/thedeveloper/warlock)  [![npm package](https://img.shields.io/npm/v/npmtest-node-redis-warlock.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-redis-warlock) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-redis-warlock.svg)](https://travis-ci.org/npmtest/node-npmtest-node-redis-warlock)

#### Battle-hardened distributed locking using redis

[![NPM](https://nodei.co/npm/node-redis-warlock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-redis-warlock)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-redis-warlock/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-redis-warlock/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-redis-warlock/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-redis-warlock/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-redis-warlock/build/test-report.html](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-redis-warlock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Geoff Wagstaff"
    },
    "bugs": {
        "url": "https://github.com/thedeveloper/warlock/issues"
    },
    "dependencies": {
        "node-redis-scripty": "0.0.5",
        "uuid": "^2.0.1"
    },
    "description": "Battle-hardened distributed locking using redis",
    "devDependencies": {
        "async": "^1.5.1",
        "mocha": "^2.3.4",
        "redis": "^2.4.2",
        "should": "^8.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "56395b994c828e8e32f6aae53b93b6edfcd97990",
        "tarball": "https://registry.npmjs.org/node-redis-warlock/-/node-redis-warlock-0.2.0.tgz"
    },
    "gitHead": "13765ee86abe008aed492fc0015a8b87f77af2b7",
    "homepage": "https://github.com/thedeveloper/warlock",
    "keywords": [
        "node.js",
        "redis",
        "lock"
    ],
    "license": "MIT",
    "main": "lib/warlock.js",
    "maintainers": [
        {
            "name": "thedeveloper"
        }
    ],
    "name": "node-redis-warlock",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/thedeveloper/warlock.git"
    },
    "scripts": {
        "bench": "mocha -R list ./test/bench",
        "test": "mocha -R list ./test/warlock"
    },
    "version": "0.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
