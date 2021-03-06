# npmdoc-seedrandom

#### basic api documentation for  [seedrandom (v2.4.3)](http://davidbau.com/archives/2010/01/30/random_seeds_coded_hints_and_quintillions.html)  [![npm package](https://img.shields.io/npm/v/npmdoc-seedrandom.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-seedrandom) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-seedrandom.svg)](https://travis-ci.org/npmdoc/node-npmdoc-seedrandom)

#### Seeded random number generator for Javascript.

[![NPM](https://nodei.co/npm/seedrandom.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/seedrandom)

- [https://npmdoc.github.io/node-npmdoc-seedrandom/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-seedrandom/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-seedrandom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-seedrandom/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-seedrandom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-seedrandom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Bau"
    },
    "browser": {
        "crypto": false
    },
    "bugs": {
        "url": "https://github.com/davidbau/seedrandom/issues"
    },
    "config": {
        "blanket": {
            "pattern": [
                "seedrandom.js",
                "lib/alea.js",
                "lib/xor128.js",
                "lib/xorwow.js",
                "lib/xorshift7.js",
                "lib/tychei.js",
                "lib/xor4096.js"
            ]
        }
    },
    "dependencies": {},
    "description": "Seeded random number generator for Javascript.",
    "devDependencies": {
        "blanket": "latest",
        "grunt": "latest",
        "grunt-bowercopy": "latest",
        "grunt-browserify": "latest",
        "grunt-cli": "latest",
        "grunt-contrib-connect": "latest",
        "grunt-contrib-qunit": "latest",
        "grunt-contrib-uglify": "latest",
        "grunt-mocha-cov": "latest",
        "grunt-release": "latest",
        "phantomjs-prebuilt": "latest",
        "proxyquire": "latest",
        "requirejs": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "2438504dad33917314bff18ac4d794f16d6aaecc",
        "tarball": "https://registry.npmjs.org/seedrandom/-/seedrandom-2.4.3.tgz"
    },
    "gitHead": "fb0b577c76938ba2b438835073de218fae3e2c3a",
    "homepage": "http://davidbau.com/archives/2010/01/30/random_seeds_coded_hints_and_quintillions.html",
    "keywords": [
        "seed",
        "random",
        "crypto"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "davidbau"
        }
    ],
    "name": "seedrandom",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/davidbau/seedrandom.git"
    },
    "scripts": {
        "test": "grunt travis"
    },
    "version": "2.4.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
