# npmdoc-neo4j-driver

#### api documentation for  neo4j-driver (v1.2.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-neo4j-driver.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-neo4j-driver) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-neo4j-driver.svg)](https://travis-ci.org/npmdoc/node-npmdoc-neo4j-driver)

#### Connect to Neo4j 3.1.0 and up from JavaScript

[![NPM](https://nodei.co/npm/neo4j-driver.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/neo4j-driver)

- [https://npmdoc.github.io/node-npmdoc-neo4j-driver/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-neo4j-driver/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-neo4j-driver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-neo4j-driver/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-neo4j-driver/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-neo4j-driver/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "neo4j-driver",
    "version": "1.2.0",
    "description": "Connect to Neo4j 3.1.0 and up from JavaScript",
    "author": "Neo Technology Inc.",
    "license": "Apache-2.0",
    "repository": {
        "type": "git",
        "url": "git://github.com/neo4j/neo4j-javascript-driver.git"
    },
    "scripts": {
        "test": "gulp test",
        "boltkit": "gulp test-boltkit",
        "build": "gulp all",
        "start-neo4j": "gulp start-neo4j",
        "stop-neo4j": "gulp stop-neo4j",
        "run-tck": "gulp run-tck",
        "docs": "esdoc -c esdoc.json",
        "versionRelease": "gulp set --version $VERSION && npm version $VERSION --no-git-tag-version"
    },
    "main": "lib/index.js",
    "devDependencies": {
        "babel-core": "^6.17.0",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-preset-es2015": "^6.16.0",
        "babel-preset-stage-3": "^6.17.0",
        "babel-register": "^6.18.0",
        "babelify": "^7.3.0",
        "browserify": "^13.1.0",
        "esdoc": "0.4.8",
        "esdoc-importpath-plugin": "0.1.1",
        "fs-extra": "^1.0.0",
        "glob": "^5.0.14",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-batch": "^1.0.5",
        "gulp-concat": "^2.6.0",
        "gulp-cucumber": "0.0.14",
        "gulp-decompress": "^1.2.0",
        "gulp-download": "^0.0.1",
        "gulp-file": "^0.3.0",
        "gulp-if": "^1.2.5",
        "gulp-install": "^0.6.0",
        "gulp-jasmine": "^2.1.0",
        "gulp-jasmine-browser": "^0.2.3",
        "gulp-replace": "^0.5.4",
        "gulp-shell": "^0.4.3",
        "gulp-uglify": "^1.4.2",
        "gulp-util": "^3.0.6",
        "gulp-watch": "^4.3.5",
        "jasmine-reporters": "^2.0.7",
        "lolex": "^1.5.2",
        "merge-stream": "^1.0.0",
        "minimist": "^1.2.0",
        "mustache": "^2.3.0",
        "phantomjs-prebuilt": "^2.1.7 ",
        "run-sequence": "^1.1.4",
        "semver": "^5.3.0",
        "through2": "~2.0.0",
        "tmp": "0.0.31",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "dependencies": {
        "babel-runtime": "^6.18.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
