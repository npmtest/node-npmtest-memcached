# npmtest-memcached

#### test coverage for  [memcached (v2.2.2)](https://github.com/3rd-Eden/node-memcached#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-memcached.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-memcached) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-memcached.svg)](https://travis-ci.org/npmtest/node-npmtest-memcached)

#### A fully featured Memcached API client, supporting both single and clustered Memcached servers through consistent hashing and failover/failure. Memcached is rewrite of nMemcached, which will be deprecated in the near future.

[![NPM](https://nodei.co/npm/memcached.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/memcached)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-memcached/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-memcached/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-memcached/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-memcached/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-memcached/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-memcached/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-memcached/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-memcached/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-memcached/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-memcached/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-memcached/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-memcached/build/test-report.html](https://npmtest.github.io/node-npmtest-memcached/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-memcached/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-memcached/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-memcached/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-memcached/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-memcached/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-memcached/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-memcached/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-memcached/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnout Kazemier"
    },
    "bugs": {
        "url": "https://github.com/3rd-Eden/node-memcached/issues"
    },
    "dependencies": {
        "hashring": "3.2.x",
        "jackpot": ">=0.0.6"
    },
    "description": "A fully featured Memcached API client, supporting both single and clustered Memcached servers through consistent hashing and failover/failure. Memcached is rewrite of nMemcached, which will be deprecated in the near future.",
    "devDependencies": {
        "mocha": "*",
        "pre-commit": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "68f86ccfd84bcf93cc25ed46d6d7fc0c7521c9d5",
        "tarball": "https://registry.npmjs.org/memcached/-/memcached-2.2.2.tgz"
    },
    "gitHead": "83a6752842665cf14b7cccf37de85b02fc07f5d5",
    "homepage": "https://github.com/3rd-Eden/node-memcached#readme",
    "keywords": [
        "InnoDB memcached API",
        "cache",
        "client",
        "cluster",
        "failover",
        "hashing",
        "membase",
        "memcache",
        "memcached",
        "nMemcached",
        "nosql"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "ronkorving"
        },
        {
            "name": "v1"
        },
        {
            "name": "3rdeden"
        }
    ],
    "name": "memcached",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/3rd-Eden/node-memcached.git"
    },
    "scripts": {
        "test": "mocha $(find test -name '*.test.js')"
    },
    "version": "2.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
