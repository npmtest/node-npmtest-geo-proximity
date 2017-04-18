# npmtest-geo-proximity

test coverage for  [geo-proximity (v2.3.2)](https://github.com/arjunmehta/node-geo-proximity)  [![npm package](https://img.shields.io/npm/v/npmtest-geo-proximity.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-geo-proximity) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-geo-proximity.svg)](https://travis-ci.org/npmtest/node-npmtest-geo-proximity)
#### Super fast proximity searches of geo coordinates.

[![NPM](https://nodei.co/npm/geo-proximity.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/geo-proximity)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-geo-proximity/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-geo-proximity/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-geo-proximity/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-geo-proximity/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-geo-proximity/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-geo-proximity/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-geo-proximity/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-geo-proximity/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-geo-proximity/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-geo-proximity/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-geo-proximity/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-geo-proximity/build/test-report.html](https://npmtest.github.io/node-npmtest-geo-proximity/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-geo-proximity/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-geo-proximity/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-geo-proximity/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-geo-proximity/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-geo-proximity/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-geo-proximity/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-geo-proximity/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-geo-proximity/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arjun Mehta",
        "url": "http://www.arjunmehta.net/"
    },
    "browser": "browser.js",
    "bugs": {
        "url": "https://github.com/arjunmehta/node-geo-proximity/issues"
    },
    "dependencies": {
        "ngeohash": "~0.6.0"
    },
    "deprecated": "Deprecated in favour of GeoRedis: www.npmjs.com/georedis | github.com/arjunmehta/node-georedis",
    "description": "Super fast proximity searches of geo coordinates.",
    "devDependencies": {
        "browserify": "~9.0.3",
        "chai": "~2.1.0",
        "mocha": "~2.1.0",
        "mocha-phantomjs": "~3.5.3",
        "nodeunit": "~0.9.0",
        "redis": "~0.10.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7d0ac5a6423b450c9ffc5c08e173f09ab2c3f5b5",
        "tarball": "https://registry.npmjs.org/geo-proximity/-/geo-proximity-2.3.2.tgz"
    },
    "gitHead": "26ef0f594e0f04deabe6d1ccb5d439217c0a2f15",
    "homepage": "https://github.com/arjunmehta/node-geo-proximity",
    "keywords": [
        "geohash",
        "proximity",
        "nearby",
        "locations",
        "spatial index",
        "2D spatial index",
        "spatial",
        "index",
        "redis",
        "geolocation",
        "geoproximity",
        "radius"
    ],
    "license": "MIT",
    "main": "./main",
    "maintainers": [
        {
            "name": "arjunmehta"
        }
    ],
    "name": "geo-proximity",
    "optionalDependencies": {},
    "repository": {
        "url": "git+https://github.com/arjunmehta/node-geo-proximity.git"
    },
    "scripts": {
        "test": "nodeunit test/test.js && browserify test/browser_test.js -o test/browser_test_compiled.js && echo '\n  Testing in Browser' && mocha-phantomjs test/browser.html"
    },
    "version": "2.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
