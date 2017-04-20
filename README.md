# npmtest-angularfire2

#### basic test coverage for  [angularfire2 (v2.0.0-beta.8)](https://github.com/angular/angularfire2#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-angularfire2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angularfire2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angularfire2.svg)](https://travis-ci.org/npmtest/node-npmtest-angularfire2)

#### <p align="center">   <h1 align="center">AngularFire2</h1>   <p align="center">The official library for Firebase and Angular 2</p> </p>

[![NPM](https://nodei.co/npm/angularfire2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angularfire2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angularfire2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angularfire2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angularfire2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angularfire2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angularfire2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angularfire2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angularfire2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angularfire2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angularfire2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angularfire2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angularfire2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angularfire2/build/test-report.html](https://npmtest.github.io/node-npmtest-angularfire2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angularfire2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angularfire2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angularfire2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angularfire2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angularfire2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angularfire2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angularfire2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angularfire2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "jeffbcross,davideast"
    },
    "bugs": {
        "url": "https://github.com/angular/angularfire2/issues"
    },
    "dependencies": {},
    "description": "<p align=\"center\">   <h1 align=\"center\">AngularFire2</h1>   <p align=\"center\">The official library for Firebase and Angular 2</p> </p>",
    "devDependencies": {
        "@angular/compiler-cli": "^2.0.0",
        "@angular/platform-server": "^2.0.0-rc.5",
        "@types/jasmine": "^2.5.36",
        "@types/request": "0.0.30",
        "concurrently": "^2.2.0",
        "conventional-changelog-cli": "^1.2.0",
        "es6-module-loader": "^0.17.10",
        "es6-shim": "^0.35.0",
        "gulp": "^3.9.0",
        "gulp-jasmine": "^2.2.1",
        "gulp-typescript": "^2.10.0",
        "http-server": "^0.8.5",
        "jasmine": "^2.4.1",
        "jasmine-core": "^2.4.1",
        "json": "^9.0.3",
        "karma": "^0.13.19",
        "karma-chrome-launcher": "^0.2.2",
        "karma-firefox-launcher": "^0.1.7",
        "karma-jasmine": "^0.3.6",
        "karma-mocha-reporter": "^2.0.2",
        "karma-systemjs": "^0.10.0",
        "ncp": "^2.0.0",
        "parse5": "^1.3.2",
        "protractor": "3.0.0",
        "reflect-metadata": "0.1.2",
        "rimraf": "^2.5.4",
        "rollup": "^0.35.11",
        "rollup-watch": "^2.5.0",
        "systemjs": "^0.19.16",
        "systemjs-builder": "^0.15.7",
        "traceur": "0.0.96",
        "typedoc": "github:jeffbcross/typedoc",
        "typescript": "^2.0.2",
        "zone.js": "^0.7.2"
    },
    "directories": {},
    "dist": {
        "shasum": "8ec172ff17448c3ccdb79e9c6179da556ff05e1b",
        "tarball": "https://registry.npmjs.org/angularfire2/-/angularfire2-2.0.0-beta.8.tgz"
    },
    "homepage": "https://github.com/angular/angularfire2#readme",
    "keywords": [
        "angular2",
        "angular",
        "firebase"
    ],
    "license": "MIT",
    "main": "bundles/angularfire2.umd.js",
    "maintainers": [
        {
            "name": "angularcore"
        },
        {
            "name": "davideast"
        },
        {
            "name": "jeffbcross"
        }
    ],
    "module": "index.js",
    "name": "angularfire2",
    "optionalDependencies": {},
    "peerDependencies": {
        "@angular/common": "^2.0.0",
        "@angular/compiler": "^2.0.0",
        "@angular/core": "^2.0.0",
        "@angular/platform-browser": "^2.0.0",
        "@angular/platform-browser-dynamic": "^2.0.0",
        "firebase": "^3.0.0",
        "rxjs": "^5.0.1"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/angular/angularfire2.git"
    },
    "scripts": {},
    "typings": "index.d.ts",
    "version": "2.0.0-beta.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
