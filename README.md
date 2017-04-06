# api documentation for  [dexie (v1.5.1)](http://dexie.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-dexie.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dexie) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dexie.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dexie)
#### A Minimalistic Wrapper for IndexedDB

[![NPM](https://nodei.co/npm/dexie.png?downloads=true)](https://www.npmjs.com/package/dexie)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dexie/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-dexie_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dexie/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dexie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dexie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Fahlander"
    },
    "bugs": {
        "url": "https://github.com/dfahlander/Dexie.js/issues"
    },
    "dependencies": {},
    "description": "A Minimalistic Wrapper for IndexedDB",
    "devDependencies": {
        "babel-cli": "^6.16.0",
        "babel-core": "^6.17.0",
        "babel-plugin-syntax-async-functions": "^6.13.0",
        "babel-plugin-transform-es2015-arrow-functions": "^6.5.2",
        "babel-plugin-transform-es2015-block-scoped-functions": "^6.6.5",
        "babel-plugin-transform-es2015-block-scoping": "^6.15.0",
        "babel-plugin-transform-es2015-classes": "^6.14.0",
        "babel-plugin-transform-es2015-computed-properties": "^6.6.5",
        "babel-plugin-transform-es2015-literals": "^6.5.0",
        "babel-plugin-transform-es2015-object-super": "^6.6.5",
        "babel-plugin-transform-es2015-parameters": "^6.17.0",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.5.0",
        "babel-plugin-transform-es2015-spread": "^6.6.5",
        "babel-plugin-transform-es2015-sticky-regex": "^6.5.0",
        "babel-plugin-transform-es2015-template-literals": "^6.6.5",
        "babel-plugin-transform-regenerator": "^6.16.1",
        "babel-polyfill": "^6.16.0",
        "babel-preset-es2015": "^6.16.0",
        "es6-promisify": "^5.0.0",
        "es6-promisify-all": "^0.1.0",
        "eslint": "^3.7.1",
        "karma": "^0.13.22",
        "karma-browserstack-launcher": "^1.1.1",
        "karma-chrome-launcher": "^2.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha-reporter": "^2.2.0",
        "karma-qunit": "^1.2.1",
        "node-watch": "^0.4.0",
        "qunit": "^0.7.7",
        "qunitjs": "^1.14.0",
        "rollup": "^0.36.1",
        "serve-static": "^1.11.1",
        "uglify-js": "^2.7.3"
    },
    "directories": {},
    "dist": {
        "shasum": "ac3ad5a0ebaf7e6e42760db58710418d4a756624",
        "tarball": "https://registry.npmjs.org/dexie/-/dexie-1.5.1.tgz"
    },
    "engines": {
        "node": ">=4.2"
    },
    "gitHead": "af57a0ad6ce21eb3f9a4f527b12a63b18326ef70",
    "homepage": "http://dexie.org",
    "jsnext:main": "dist/dexie.es6.js",
    "jspm": {
        "format": "cjs",
        "ignore": [
            "src/"
        ]
    },
    "keywords": [
        "indexeddb",
        "browser",
        "database"
    ],
    "license": "Apache-2.0",
    "main": "dist/dexie.js",
    "maintainers": [
        {
            "name": "anders.ekdahl",
            "email": "anders.ekdahl@gmail.com"
        },
        {
            "name": "dfahlander",
            "email": "david.fahlander@gmail.com"
        }
    ],
    "name": "dexie",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dfahlander/Dexie.js.git"
    },
    "scripts": {
        "build": "babel-node --presets es2015 --plugins syntax-async-functions,transform-regenerator tools/build.js",
        "eslint": "eslint src",
        "test": "npm run eslint && npm run build && npm run test:local",
        "test:debug": "karma start test/karma.conf.js --log-level debug",
        "test:local": "karma start test/karma.conf.js --single-run",
        "test:release": "karma start test/karma.release.conf.js --single-run",
        "watch": "babel-node --presets es2015 --plugins syntax-async-functions,transform-regenerator tools/watch.js"
    },
    "typings": "dist/dexie.d.ts",
    "version": "1.5.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module dexie](#apidoc.module.dexie)



# <a name="apidoc.module.dexie"></a>[module dexie](#apidoc.module.dexie)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
