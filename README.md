# api documentation for  [isomorphic-fetch (v2.2.1)](https://github.com/matthew-andrews/isomorphic-fetch/issues)  [![npm package](https://img.shields.io/npm/v/npmdoc-isomorphic-fetch.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-isomorphic-fetch) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-isomorphic-fetch.svg)](https://travis-ci.org/npmdoc/node-npmdoc-isomorphic-fetch)
#### Isomorphic WHATWG Fetch API, for Node & Browserify

[![NPM](https://nodei.co/npm/isomorphic-fetch.png?downloads=true)](https://www.npmjs.com/package/isomorphic-fetch)

[![apidoc](https://npmdoc.github.io/node-npmdoc-isomorphic-fetch/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-isomorphic-fetch%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-isomorphic-fetch/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-isomorphic-fetch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-isomorphic-fetch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Andrews",
        "email": "matt@mattandre.ws"
    },
    "browser": "fetch-npm-browserify.js",
    "bugs": {
        "url": "https://github.com/matthew-andrews/isomorphic-fetch/issues"
    },
    "dependencies": {
        "node-fetch": "^1.0.1",
        "whatwg-fetch": ">=0.10.0"
    },
    "description": "Isomorphic WHATWG Fetch API, for Node & Browserify",
    "devDependencies": {
        "chai": "^1.10.0",
        "es6-promise": "^2.0.1",
        "jshint": "^2.5.11",
        "lintspaces-cli": "0.0.4",
        "mocha": "^2.1.0",
        "nock": "^0.56.0",
        "npm-prepublish": "^1.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "611ae1acf14f5e81f729507472819fe9733558a9",
        "tarball": "https://registry.npmjs.org/isomorphic-fetch/-/isomorphic-fetch-2.2.1.tgz"
    },
    "gitHead": "43437dc5b381e391b73522d71cea23fc72675154",
    "homepage": "https://github.com/matthew-andrews/isomorphic-fetch/issues",
    "license": "MIT",
    "main": "fetch-npm-node.js",
    "maintainers": [
        {
            "name": "financial-times",
            "email": "strategic.products@ft.com"
        },
        {
            "name": "mattandrews",
            "email": "matt@mattandre.ws"
        }
    ],
    "name": "isomorphic-fetch",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/matthew-andrews/isomorphic-fetch.git"
    },
    "scripts": {
        "files": "find . -name '*.js' ! -path './node_modules/*' ! -path './bower_components/*'",
        "test": "jshint 'npm run -s files' && lintspaces -i js-comments -e .editorconfig 'npm run -s files' && mocha"
    },
    "version": "2.2.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module isomorphic-fetch](#apidoc.module.isomorphic-fetch)



# <a name="apidoc.module.isomorphic-fetch"></a>[module isomorphic-fetch](#apidoc.module.isomorphic-fetch)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
