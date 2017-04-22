# npmdoc-unicode

#### api documentation for  [unicode (v9.0.1)](http://github.com/eversport/node-unicodetable)  [![npm package](https://img.shields.io/npm/v/npmdoc-unicode.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-unicode) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-unicode.svg)](https://travis-ci.org/npmdoc/node-npmdoc-unicode)

#### unicode lookup table

[![NPM](https://nodei.co/npm/unicode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/unicode)

- [https://npmdoc.github.io/node-npmdoc-unicode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-unicode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-unicode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-unicode/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-unicode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-unicode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "unicode",
    "description": "unicode lookup table",
    "version": "9.0.1",
    "author": "dodo (https://github.com/dodo)",
    "contributors": [
        "Mathias Bynens <mathias@qiwi.be> (http://mathiasbynens.be/)",
        "Thomas Danecker <thomas.danecker@eversports.com>"
    ],
    "homepage": "http://github.com/eversport/node-unicodetable",
    "repository": {
        "type": "git",
        "url": "git://github.com/eversport/node-unicodetable.git"
    },
    "engines": {
        "node": ">= 0.8.x"
    },
    "scripts": {
        "download": "curl \"http://unicode.org/Public/9.0.0/ucd/UnicodeData.txt\" > UnicodeData.txt",
        "generate": "node generate.js",
        "test": "node test.js",
        "np": "np"
    },
    "devDependencies": {
        "bufferstream": ">= 0.6.2",
        "np": "2.13.1"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/dodo/node-unicodetable/raw/master/LICENSE"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
