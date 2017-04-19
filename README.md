# npmdoc-swagger-ui

#### api documentation for  [swagger-ui (v3.0.6)](https://github.com/swagger-api/swagger-ui#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-swagger-ui.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-swagger-ui) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-swagger-ui.svg)](https://travis-ci.org/npmdoc/node-npmdoc-swagger-ui)

#### [![NPM version](https://badge.fury.io/js/swagger-ui.svg)](http://badge.fury.io/js/swagger-ui)

[![NPM](https://nodei.co/npm/swagger-ui.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swagger-ui)

- [https://npmdoc.github.io/node-npmdoc-swagger-ui/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swagger-ui/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger-ui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger-ui/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-swagger-ui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-swagger-ui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browserslist": [
        "> 1%",
        "last 2 versions",
        "IE 10"
    ],
    "bugs": {
        "url": "https://github.com/swagger-api/swagger-ui/issues"
    },
    "config": {
        "deps_check_dir": ".deps_check"
    },
    "contributors": [
        {
            "url": "in alphabetical order"
        },
        {
            "name": "Anna Bodnia"
        },
        {
            "name": "Buu Nguyen"
        },
        {
            "name": "Josh Ponelat"
        },
        {
            "name": "Kyle Shockey"
        },
        {
            "name": "Robert Barnwell"
        },
        {
            "name": "Sahar Jafari"
        }
    ],
    "dependencies": {
        "babel-polyfill": "^6.23.0",
        "brace": "0.7.0",
        "deep-extend": "0.4.1",
        "expect": "1.20.2",
        "getbase": "^2.8.2",
        "immutable": "^3.x.x",
        "js-yaml": "^3.5.5",
        "less": "2.7.1",
        "lodash": "4.17.2",
        "matcher": "^0.1.2",
        "memoizee": "0.4.1",
        "promise-worker": "^1.1.1",
        "react": "^15.4.0",
        "react-addons-perf": "0.14.8",
        "react-addons-shallow-compare": "0.14.8",
        "react-addons-test-utils": "^15.4.0",
        "react-collapse": "2.3.1",
        "react-dom": "^15.4.0",
        "react-height": "^2.0.0",
        "react-hot-loader": "1.3.1",
        "react-immutable-proptypes": "2.1.0",
        "react-motion": "0.4.4",
        "react-object-inspector": "0.2.1",
        "react-redux": "^4.x.x",
        "react-remarkable": "1.1.1",
        "react-split-pane": "0.1.57",
        "redux": "^3.x.x",
        "redux-immutable": "3.0.8",
        "redux-logger": "*",
        "reselect": "2.5.3",
        "serialize-error": "2.0.0",
        "shallowequal": "0.2.2",
        "swagger-client": "^3.0.5",
        "url-parse": "^1.1.8",
        "webpack-dev-server": "1.14.0",
        "whatwg-fetch": "0.11.1",
        "worker-loader": "^0.7.1",
        "xml": "1.0.1",
        "yaml-js": "^0.1.3"
    },
    "description": "[![NPM version](https://badge.fury.io/js/swagger-ui.svg)](http://badge.fury.io/js/swagger-ui)",
    "devDependencies": {
        "autoprefixer": "6.6.1",
        "babel-core": "^6.23.1",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.3.2",
        "babel-plugin-module-alias": "^1.6.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-es2015-ie": "^6.6.2",
        "babel-preset-react": "^6.23.0",
        "babel-preset-stage-0": "^6.22.0",
        "babel-runtime": "^6.23.0",
        "css-loader": "0.22.0",
        "deep-extend": "^0.4.1",
        "deepmerge": "^1.3.2",
        "enzyme": "^2.7.1",
        "eslint": "^2.13.1",
        "eslint-plugin-react": "^6.10.3",
        "extract-text-webpack-plugin": "0.8.2",
        "file-loader": "0.8.4",
        "html-webpack-plugin": "^2.28.0",
        "imports-loader": "0.6.5",
        "json-loader": "0.5.3",
        "karma": "^0.13.22",
        "karma-chrome-launcher": "^0.2.3",
        "karma-mocha": "^0.2.2",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "1.8.0",
        "less": "2.5.3",
        "less-loader": "2.2.1",
        "license-checker": "^8.0.4",
        "mocha": "^2.5.3",
        "node-sass": "^4.5.0",
        "npm-run-all": "3.1.1",
        "null-loader": "0.1.1",
        "open": "0.0.5",
        "postcss-loader": "0.7.0",
        "raw-loader": "0.5.1",
        "react-hot-loader": "^1.3.1",
        "react-test-renderer": "^15.5.4",
        "rimraf": "^2.6.0",
        "sass-loader": "^6.0.2",
        "standard": "^8.6.0",
        "standard-loader": "^5.0.0",
        "style-loader": "0.13.0",
        "url-loader": "0.5.6",
        "webpack": "^1.14.0",
        "webpack-bundle-size-analyzer": "^2.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d8e391a083790803bd36a364b074f9bebba2ccd6",
        "tarball": "https://registry.npmjs.org/swagger-ui/-/swagger-ui-3.0.6.tgz"
    },
    "gitHead": "db8bd52f16d8ada64e5e281596534a7e36bb86af",
    "homepage": "https://github.com/swagger-api/swagger-ui#readme",
    "license": "Apache-2.0",
    "main": "dist/swagger-ui.js",
    "maintainers": [
        {
            "name": "fehguy"
        },
        {
            "name": "swagger-api"
        }
    ],
    "name": "swagger-ui",
    "optionalDependencies": {
        "webpack-dev-server": "1.14.0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/swagger-api/swagger-ui.git"
    },
    "scripts": {
        "build": "npm run build-core && npm run build-bundle && npm run build-standalone",
        "build-bundle": "webpack --config webpack-dist-bundle.config.js --colors",
        "build-core": "webpack --config webpack-dist.config.js --colors",
        "build-standalone": "webpack --config webpack-dist-standalone.config.js --colors",
        "deps-check": "npm run deps-license && npm run deps-size",
        "deps-license": "license-checker --production --csv --out $npm_package_config_deps_check_dir/licenses.csv && license-checker --development --csv --out $npm_package_config_deps_check_dir/licenses-dev.csv",
        "deps-size": "webpack -p --config webpack.check.js --json | webpack-bundle-size-analyzer >| $npm_package_config_deps_check_dir/sizes.txt",
        "dev": "npm-run-all --parallel hot-server watch  open-localhost",
        "hot-server": "webpack-dev-server --host 0.0.0.0 --config webpack-hot-dev-server.config.js --inline --hot --progress --content-base dev-helpers/",
        "just-test": "karma start --config karma.conf.js",
        "just-test-in-node": "mocha --recursive --compilers js:babel-core/register test/core test/components",
        "lint": "eslint --cache --ext '.js,.jsx' src test",
        "lint-errors": "eslint --cache --quiet --ext '.js,.jsx' src test",
        "lint-fix": "eslint --cache --ext '.js,.jsx' src test --fix",
        "open-localhost": "node -e 'require(\"open\")(\"http://localhost:3200\")'",
        "predev": "npm install",
        "test": "npm run lint-errors && npm run just-test-in-node",
        "test-in-node": "npm run lint-errors && npm run just-test-in-node",
        "watch": "webpack --config webpack-watch.config.js --watch --progress"
    },
    "version": "3.0.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
