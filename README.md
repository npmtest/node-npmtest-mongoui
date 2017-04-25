# npmtest-mongoui

#### basic test coverage for  [mongoui (v4.0.6)](https://github.com/azat-co/mongoui#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mongoui.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mongoui) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mongoui.svg)](https://travis-ci.org/npmtest/node-npmtest-mongoui)

#### MongoUI is an open-source web and desktop app which allows to administer local and remote MongoDB instances via GUI. No need to type commands in a terminal anymore. Convenient interface will allow to create, update, remove and filter/search documents. You

[![NPM](https://nodei.co/npm/mongoui.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongoui)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mongoui/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongoui/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mongoui/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mongoui/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mongoui/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mongoui/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mongoui/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mongoui/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mongoui/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mongoui/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mongoui/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongoui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mongoui/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mongoui/build/test-report.html](https://npmtest.github.io/node-npmtest-mongoui/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mongoui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mongoui/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mongoui/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongoui/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongoui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongoui/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mongoui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mongoui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "babel": {
        "presets": [
            "react",
            "es2015"
        ]
    },
    "bin": {
        "mongoui": "./index.js"
    },
    "bugs": {
        "url": "https://github.com/azat-co/mongoui/issues"
    },
    "dependencies": {
        "body-parser": "^1.15.0",
        "compression": "^1.6.1",
        "cors": "^2.7.1",
        "deep-equal": "^1.0.1",
        "errorhandler": "^1.4.3",
        "express": "^4.13.4",
        "express-handlebars": "^3.0.0",
        "mongodb": "^2.1.11",
        "mongoskin": "2.0.3",
        "neo-async": "1.8.0",
        "react": "^15.0.1",
        "react-bootstrap": "0.30",
        "react-copy-to-clipboard": "^4.1.0",
        "react-dom": "^15.0.1",
        "react-highlight": "^0.8.0",
        "react-redux": "4.4.1",
        "react-router": "^2.2.2",
        "redux": "3.3.1",
        "require-dir": "^0.3.0",
        "serve-favicon": "^2.3.0"
    },
    "description": "MongoUI is an open-source web and desktop app which allows to administer local and remote MongoDB instances via GUI. No need to type commands in a terminal anymore. Convenient interface will allow to create, update, remove and filter/search documents. You",
    "devDependencies": {
        "babel-core": "^6.7.4",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "chai": "^3.5.0",
        "concurrently": "^2.2.0",
        "css-loader": "^0.23.1",
        "expect": "1.16.0",
        "json-loader": "^0.5.4",
        "mocha": "2.4.5",
        "nodemon": "^1.9.1",
        "react-hot-loader": "^1.3.0",
        "redux-devtools": "3.1.1",
        "request": "^2.69.0",
        "style-loader": "^0.13.1",
        "supertest": "^1.2.0",
        "webpack": "^1.13.0",
        "webpack-dev-server": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "de563254a81897e3882077495c8ee905aab9f060",
        "tarball": "https://registry.npmjs.org/mongoui/-/mongoui-4.0.6.tgz"
    },
    "engines": {
        "node": ">= v6.x"
    },
    "gitHead": "ded0c573bc53bf4884fb515aa25d23695853f30d",
    "homepage": "https://github.com/azat-co/mongoui#readme",
    "license": "SEE IN LICENSE.md",
    "maintainers": [
        {
            "name": "azat"
        }
    ],
    "mongoui": {
        "apiPort": 3001,
        "apiUrl": "http://localhost"
    },
    "name": "mongoui",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/azat-co/mongoui.git"
    },
    "scripts": {
        "api-server": "node node_modules/.bin/nodemon index.js",
        "build": "node node_modules/.bin/webpack --config webpack.start.config.js",
        "clean": "rm -f ./public/js/bundle.js",
        "dev": "npm run clean && node node_modules/webpack-dev-server/bin/webpack-dev-server.js --content-base public --hot",
        "dev-server": "node dev-server.js",
        "preversion": "npm run build",
        "start": "npm run clean && npm run build && node node_modules/.bin/nodemon index.js",
        "start-dev": "concurrently 'npm run dev' 'npm run api-server' 'npm run dev-server'",
        "test": "mocha test"
    },
    "version": "4.0.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
