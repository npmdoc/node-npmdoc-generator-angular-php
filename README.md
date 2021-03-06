# npmdoc-generator-angular-php

#### basic api documentation for  [generator-angular-php (v0.6.3)](https://github.com/amercier/generator-angular-php)  [![npm package](https://img.shields.io/npm/v/npmdoc-generator-angular-php.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-generator-angular-php) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-generator-angular-php.svg)](https://travis-ci.org/npmdoc/node-npmdoc-generator-angular-php)

#### Yeoman generator for AngularJS with a PHP backend. Based on generator-angular. /api is redirected by grunt-connect-proxy to the PHP built-in server using grunt-php

[![NPM](https://nodei.co/npm/generator-angular-php.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-angular-php)

- [https://npmdoc.github.io/node-npmdoc-generator-angular-php/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-angular-php/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-angular-php/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-angular-php/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-generator-angular-php/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-generator-angular-php/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexandre Mercier"
    },
    "bugs": {
        "url": "https://github.com/amercier/generator-angular-php/issues"
    },
    "dependencies": {
        "chalk": "^0.4.0",
        "wiredep": "^1.8.6",
        "yeoman-generator": "^0.16.0",
        "yosay": "^0.2.0"
    },
    "description": "Yeoman generator for AngularJS with a PHP backend. Based on generator-angular. /api is redirected by grunt-connect-proxy to the PHP built-in server using grunt-php",
    "devDependencies": {
        "grunt": "~0.4.5",
        "grunt-contrib-jshint": "~0.10.0",
        "grunt-conventional-changelog": "~1.1.0",
        "grunt-release": "~0.6.0",
        "load-grunt-tasks": "~0.3.0",
        "mocha": "~2.0.0",
        "semver": "~2.3.0",
        "underscore.string": "~2.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "83e765a5c0e03a738733046680002189eb69ea1f",
        "tarball": "https://registry.npmjs.org/generator-angular-php/-/generator-angular-php-0.6.3.tgz"
    },
    "engines": {
        "node": ">=0.10.0",
        "npm": ">=1.2.10"
    },
    "files": [
        "app",
        "common",
        "constant",
        "controller",
        "decorator",
        "directive",
        "factory",
        "filter",
        "main",
        "provider",
        "route",
        "service",
        "templates",
        "value",
        "view",
        "script-base.js",
        "util.js"
    ],
    "gitHead": "2a828fc2a2754e9f6a1e9dfd62986473d873893d",
    "homepage": "https://github.com/amercier/generator-angular-php",
    "keywords": [
        "yeoman-generator",
        "scaffold",
        "framework",
        "component",
        "front-end",
        "app",
        "angular",
        "php"
    ],
    "licenses": [
        {
            "type": "BSD"
        }
    ],
    "main": "app/index.js",
    "maintainers": [
        {
            "name": "amercier"
        }
    ],
    "name": "generator-angular-php",
    "optionalDependencies": {},
    "peerDependencies": {
        "generator-karma": ">=0.8.3",
        "yo": ">=1.3.3"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/amercier/generator-angular-php.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "0.6.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
