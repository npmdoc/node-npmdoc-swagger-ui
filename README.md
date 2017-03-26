# api documentation for  [swagger-ui (v3.0.3)](https://github.com/swagger-api/swagger-ui#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-swagger-ui.svg)](https://travis-ci.org/npmdoc/node-npmdoc-swagger-ui)
#### [![NPM version](https://badge.fury.io/js/swagger-ui.svg)](http://badge.fury.io/js/swagger-ui)

[![NPM](https://nodei.co/npm/swagger-ui.png?downloads=true)](https://www.npmjs.com/package/swagger-ui)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger-ui/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-swagger-ui_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger-ui/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-swagger-ui/build/screen-capture.npmPackageListing.svg)



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
            "name": "Anna Bodnia",
            "email": "anna.bodnia@gmail.com"
        },
        {
            "name": "Buu Nguyen",
            "email": "buunguyen@gmail.com"
        },
        {
            "name": "Josh Ponelat",
            "email": "jponelat@gmail.com"
        },
        {
            "name": "Kyle Shockey",
            "email": "kyleshockey1@gmail.com"
        },
        {
            "name": "Robert Barnwell",
            "email": "robert@robertismy.name"
        },
        {
            "name": "Sahar Jafari",
            "email": "shr.jafari@gmail.com"
        }
    ],
    "dependencies": {
        "babel-polyfill": "^6.23.0",
        "brace": "0.7.0",
        "btoa": "^1.1.2",
        "debounce": "1.0.0",
        "deep-extend": "0.4.1",
        "expect": "1.20.2",
        "getbase": "^2.8.2",
        "immutable": "^3.x.x",
        "js-yaml": "^3.5.5",
        "jsonschema": "^1.1.0",
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
        "swagger-client": "^3.0.3",
        "webpack-dev-server": "1.14.0",
        "whatwg-fetch": "0.11.1",
        "worker-loader": "^0.7.1",
        "xml": "1.0.1",
        "yaml-js": "^0.1.3",
        "yaml-worker": "^2.1.0"
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
        "shasum": "72d7134ed80d2211414625b1e3394e5acda85366",
        "tarball": "https://registry.npmjs.org/swagger-ui/-/swagger-ui-3.0.3.tgz"
    },
    "gitHead": "7827e0ab820f513f3dcf4d90cb685f84303a1ac0",
    "homepage": "https://github.com/swagger-api/swagger-ui#readme",
    "license": "Apache-2.0",
    "main": "dist/swagger-ui.js",
    "maintainers": [
        {
            "name": "fehguy",
            "email": "fehguy@gmail.com"
        },
        {
            "name": "swagger-api",
            "email": "apiteam@swagger.io"
        }
    ],
    "name": "swagger-ui",
    "optionalDependencies": {
        "webpack-dev-server": "1.14.0"
    },
    "readme": "ERROR: No README data found!",
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
        "hot-server": "webpack-dev-server --host 0.0.0.0 --config webpack-hot-dev-server.config.js --inline --hot --progress --content-base dist/",
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
    "version": "3.0.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module swagger-ui](#apidoc.module.swagger-ui)
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.All
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.AstAst
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.AuthActions
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.AuthReducers
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.AuthSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.AuthSpecWrapActions
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.ErrActions
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.ErrErrorTransformersTransformersNotOfType
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.ErrErrorTransformersTransformersParameterOneof
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.ErrErrorTransformersTransformersStripInstance
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.ErrSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.LayoutActions
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.LayoutReducers
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.LayoutSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.SamplesFn
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.SpecActions
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.SpecReducers
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.SpecSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.SpecWrapActions
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.SplitPaneModeComponentsIndex
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>plugins.ViewRootInjects
1.  object <span class="apidocSignatureSpan">swagger-ui.</span>presets

#### [module swagger-ui.plugins](#apidoc.module.swagger-ui.plugins)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AstIndex ()](#apidoc.element.swagger-ui.plugins.AstIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AstJumpToPath ()](#apidoc.element.swagger-ui.plugins.AstJumpToPath)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AuthIndex ()](#apidoc.element.swagger-ui.plugins.AuthIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>DownloadUrl (e)](#apidoc.element.swagger-ui.plugins.DownloadUrl)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrErrorTransformersHook (e, t)](#apidoc.element.swagger-ui.plugins.ErrErrorTransformersHook)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrIndex (e)](#apidoc.element.swagger-ui.plugins.ErrIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrReducers (e)](#apidoc.element.swagger-ui.plugins.ErrReducers)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>LayoutIndex ()](#apidoc.element.swagger-ui.plugins.LayoutIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>LogsIndex (e)](#apidoc.element.swagger-ui.plugins.LogsIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SamplesIndex ()](#apidoc.element.swagger-ui.plugins.SamplesIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SpecIndex ()](#apidoc.element.swagger-ui.plugins.SpecIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SplitPaneModeComponentsSplitPaneMode ()](#apidoc.element.swagger-ui.plugins.SplitPaneModeComponentsSplitPaneMode)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SplitPaneModeIndex ()](#apidoc.element.swagger-ui.plugins.SplitPaneModeIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SwaggerJsIndex (e)](#apidoc.element.swagger-ui.plugins.SwaggerJsIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>UtilIndex ()](#apidoc.element.swagger-ui.plugins.UtilIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ViewIndex (e)](#apidoc.element.swagger-ui.plugins.ViewIndex)
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>All
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AstAst
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AuthActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AuthReducers
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AuthSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AuthSpecWrapActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrErrorTransformersTransformersNotOfType
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrErrorTransformersTransformersParameterOneof
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrErrorTransformersTransformersStripInstance
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>LayoutActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>LayoutReducers
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>LayoutSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SamplesFn
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SpecActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SpecReducers
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SpecSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SpecWrapActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SplitPaneModeComponentsIndex
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ViewRootInjects
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>default

#### [module swagger-ui.plugins.All](#apidoc.module.swagger-ui.plugins.All)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AstIndex ()](#apidoc.element.swagger-ui.plugins.All.AstIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AstJumpToPath ()](#apidoc.element.swagger-ui.plugins.All.AstJumpToPath)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AuthIndex ()](#apidoc.element.swagger-ui.plugins.All.AuthIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>DownloadUrl (e)](#apidoc.element.swagger-ui.plugins.All.DownloadUrl)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrErrorTransformersHook (e, t)](#apidoc.element.swagger-ui.plugins.All.ErrErrorTransformersHook)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrIndex (e)](#apidoc.element.swagger-ui.plugins.All.ErrIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrReducers (e)](#apidoc.element.swagger-ui.plugins.All.ErrReducers)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>LayoutIndex ()](#apidoc.element.swagger-ui.plugins.All.LayoutIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>LogsIndex (e)](#apidoc.element.swagger-ui.plugins.All.LogsIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SamplesIndex ()](#apidoc.element.swagger-ui.plugins.All.SamplesIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SpecIndex ()](#apidoc.element.swagger-ui.plugins.All.SpecIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SplitPaneModeComponentsSplitPaneMode ()](#apidoc.element.swagger-ui.plugins.All.SplitPaneModeComponentsSplitPaneMode)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SplitPaneModeIndex ()](#apidoc.element.swagger-ui.plugins.All.SplitPaneModeIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SwaggerJsIndex (e)](#apidoc.element.swagger-ui.plugins.All.SwaggerJsIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>UtilIndex ()](#apidoc.element.swagger-ui.plugins.All.UtilIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ViewIndex (e)](#apidoc.element.swagger-ui.plugins.All.ViewIndex)
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.</span>All
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AstAst
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AuthActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AuthReducers
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AuthSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AuthSpecWrapActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrErrorTransformersTransformersNotOfType
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrErrorTransformersTransformersParameterOneof
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrErrorTransformersTransformersStripInstance
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>LayoutActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>LayoutReducers
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>LayoutSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SamplesFn
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SpecActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SpecReducers
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SpecSelectors
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SpecWrapActions
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SplitPaneModeComponentsIndex
1.  object <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ViewRootInjects

#### [module swagger-ui.plugins.AstAst](#apidoc.module.swagger-ui.plugins.AstAst)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>getLineNumberForPath (e, t)](#apidoc.element.swagger-ui.plugins.AstAst.getLineNumberForPath)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>getLineNumberForPathAsync ()](#apidoc.element.swagger-ui.plugins.AstAst.getLineNumberForPathAsync)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>pathForPosition (e, t)](#apidoc.element.swagger-ui.plugins.AstAst.pathForPosition)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>pathForPositionAsync ()](#apidoc.element.swagger-ui.plugins.AstAst.pathForPositionAsync)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>positionRangeForPath (e, t)](#apidoc.element.swagger-ui.plugins.AstAst.positionRangeForPath)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>positionRangeForPathAsync ()](#apidoc.element.swagger-ui.plugins.AstAst.positionRangeForPathAsync)

#### [module swagger-ui.plugins.AuthActions](#apidoc.module.swagger-ui.plugins.AuthActions)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>authorize (e)](#apidoc.element.swagger-ui.plugins.AuthActions.authorize)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>authorizeOauth2 (e)](#apidoc.element.swagger-ui.plugins.AuthActions.authorizeOauth2)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>authorizePassword (e)](#apidoc.element.swagger-ui.plugins.AuthActions.authorizePassword)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>logout (e)](#apidoc.element.swagger-ui.plugins.AuthActions.logout)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>preAuthorizeOauth2 (e)](#apidoc.element.swagger-ui.plugins.AuthActions.preAuthorizeOauth2)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>showDefinitions (e)](#apidoc.element.swagger-ui.plugins.AuthActions.showDefinitions)
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>AUTHORIZE
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>AUTHORIZE_OAUTH2
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>LOGOUT
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>PRE_AUTHORIZE_OAUTH2
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>SHOW_AUTH_POPUP
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>VALIDATE

#### [module swagger-ui.plugins.AuthReducers](#apidoc.module.swagger-ui.plugins.AuthReducers)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthReducers.</span>authorize (e, t)](#apidoc.element.swagger-ui.plugins.AuthReducers.authorize)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthReducers.</span>authorize_oauth2 (e, t)](#apidoc.element.swagger-ui.plugins.AuthReducers.authorize_oauth2)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthReducers.</span>logout (e, t)](#apidoc.element.swagger-ui.plugins.AuthReducers.logout)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthReducers.</span>show_popup (e, t)](#apidoc.element.swagger-ui.plugins.AuthReducers.show_popup)

#### [module swagger-ui.plugins.AuthSelectors](#apidoc.module.swagger-ui.plugins.AuthSelectors)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>authorized (state, props)](#apidoc.element.swagger-ui.plugins.AuthSelectors.authorized)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>definitionsToAuthorize (state, props)](#apidoc.element.swagger-ui.plugins.AuthSelectors.definitionsToAuthorize)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>getDefinitionsByNames (e, t)](#apidoc.element.swagger-ui.plugins.AuthSelectors.getDefinitionsByNames)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>isAuthorized (e, t)](#apidoc.element.swagger-ui.plugins.AuthSelectors.isAuthorized)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>shownDefinitions (state, props)](#apidoc.element.swagger-ui.plugins.AuthSelectors.shownDefinitions)

#### [module swagger-ui.plugins.AuthSpecWrapActions](#apidoc.module.swagger-ui.plugins.AuthSpecWrapActions)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSpecWrapActions.</span>execute (e, t)](#apidoc.element.swagger-ui.plugins.AuthSpecWrapActions.execute)

#### [module swagger-ui.plugins.ErrActions](#apidoc.module.swagger-ui.plugins.ErrActions)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>clear ()](#apidoc.element.swagger-ui.plugins.ErrActions.clear)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>newAuthErr (e)](#apidoc.element.swagger-ui.plugins.ErrActions.newAuthErr)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>newSpecErr (e)](#apidoc.element.swagger-ui.plugins.ErrActions.newSpecErr)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>newThrownErr (e, t)](#apidoc.element.swagger-ui.plugins.ErrActions.newThrownErr)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>newThrownErrBatch (e)](#apidoc.element.swagger-ui.plugins.ErrActions.newThrownErrBatch)
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>CLEAR
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>NEW_AUTH_ERR
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>NEW_SPEC_ERR
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>NEW_THROWN_ERR
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>NEW_THROWN_ERR_BATCH

#### [module swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType](#apidoc.module.swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType.</span>transform (e)](#apidoc.element.swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType.transform)

#### [module swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof](#apidoc.module.swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof.</span>transform (e, t)](#apidoc.element.swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof.transform)

#### [module swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance](#apidoc.module.swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance.</span>transform (e)](#apidoc.element.swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance.transform)

#### [module swagger-ui.plugins.ErrSelectors](#apidoc.module.swagger-ui.plugins.ErrSelectors)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrSelectors.</span>allErrors (state, props)](#apidoc.element.swagger-ui.plugins.ErrSelectors.allErrors)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrSelectors.</span>lastError (state, props)](#apidoc.element.swagger-ui.plugins.ErrSelectors.lastError)

#### [module swagger-ui.plugins.LayoutActions](#apidoc.module.swagger-ui.plugins.LayoutActions)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutActions.</span>changeMode (e)](#apidoc.element.swagger-ui.plugins.LayoutActions.changeMode)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutActions.</span>show (e)](#apidoc.element.swagger-ui.plugins.LayoutActions.show)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutActions.</span>updateLayout (e)](#apidoc.element.swagger-ui.plugins.LayoutActions.updateLayout)
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutActions.</span>SHOW
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutActions.</span>UPDATE_LAYOUT
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutActions.</span>UPDATE_MODE

#### [module swagger-ui.plugins.LayoutReducers](#apidoc.module.swagger-ui.plugins.LayoutReducers)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutReducers.</span>layout_show (e, t)](#apidoc.element.swagger-ui.plugins.LayoutReducers.layout_show)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutReducers.</span>layout_update_layout (e, t)](#apidoc.element.swagger-ui.plugins.LayoutReducers.layout_update_layout)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutReducers.</span>layout_update_mode (e, t)](#apidoc.element.swagger-ui.plugins.LayoutReducers.layout_update_mode)

#### [module swagger-ui.plugins.LayoutSelectors](#apidoc.module.swagger-ui.plugins.LayoutSelectors)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutSelectors.</span>current (e)](#apidoc.element.swagger-ui.plugins.LayoutSelectors.current)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutSelectors.</span>isShown (e, t, r)](#apidoc.element.swagger-ui.plugins.LayoutSelectors.isShown)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutSelectors.</span>showSummary (state, props)](#apidoc.element.swagger-ui.plugins.LayoutSelectors.showSummary)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutSelectors.</span>whatMode (e, t)](#apidoc.element.swagger-ui.plugins.LayoutSelectors.whatMode)

#### [module swagger-ui.plugins.SamplesFn](#apidoc.module.swagger-ui.plugins.SamplesFn)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>createXMLExample (e, t)](#apidoc.element.swagger-ui.plugins.SamplesFn.createXMLExample)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>inferSchema (e)](#apidoc.element.swagger-ui.plugins.SamplesFn.inferSchema)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>memoizedCreateXMLExample (arg)](#apidoc.element.swagger-ui.plugins.SamplesFn.memoizedCreateXMLExample)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>memoizedSampleFromSchema (arg)](#apidoc.element.swagger-ui.plugins.SamplesFn.memoizedSampleFromSchema)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>sampleFromSchema (t)](#apidoc.element.swagger-ui.plugins.SamplesFn.sampleFromSchema)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>sampleXmlFromSchema (t)](#apidoc.element.swagger-ui.plugins.SamplesFn.sampleXmlFromSchema)

#### [module swagger-ui.plugins.SpecActions](#apidoc.module.swagger-ui.plugins.SpecActions)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>changeConsumesValue (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.changeConsumesValue)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>changeParam (e, t, r, n)](#apidoc.element.swagger-ui.plugins.SpecActions.changeParam)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>changeProducesValue (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.changeProducesValue)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>clearRequest (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.clearRequest)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>clearResponse (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.clearResponse)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>clearValidateParams (e)](#apidoc.element.swagger-ui.plugins.SpecActions.clearValidateParams)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>execute ()](#apidoc.element.swagger-ui.plugins.SpecActions.execute)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>executeRequest (e)](#apidoc.element.swagger-ui.plugins.SpecActions.executeRequest)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>formatIntoYaml ()](#apidoc.element.swagger-ui.plugins.SpecActions.formatIntoYaml)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>logRequest (e)](#apidoc.element.swagger-ui.plugins.SpecActions.logRequest)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>parseToJson (e)](#apidoc.element.swagger-ui.plugins.SpecActions.parseToJson)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>resolveSpec (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.resolveSpec)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>setRequest (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecActions.setRequest)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>setResponse (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecActions.setResponse)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>setScheme (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecActions.setScheme)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>updateJsonSpec (e)](#apidoc.element.swagger-ui.plugins.SpecActions.updateJsonSpec)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>updateResolved (e)](#apidoc.element.swagger-ui.plugins.SpecActions.updateResolved)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>updateSpec (e)](#apidoc.element.swagger-ui.plugins.SpecActions.updateSpec)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>updateUrl (e)](#apidoc.element.swagger-ui.plugins.SpecActions.updateUrl)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>validateParams (e)](#apidoc.element.swagger-ui.plugins.SpecActions.validateParams)
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>CLEAR_REQUEST
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>CLEAR_RESPONSE
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>ClEAR_VALIDATE_PARAMS
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>LOG_REQUEST
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>SET_REQUEST
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>SET_RESPONSE
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>SET_SCHEME
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>UPDATE_JSON
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>UPDATE_OPERATION_VALUE
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>UPDATE_PARAM
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>UPDATE_RESOLVED
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>UPDATE_SPEC
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>UPDATE_URL
1.  string <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>VALIDATE_PARAMS

#### [module swagger-ui.plugins.SpecReducers](#apidoc.module.swagger-ui.plugins.SpecReducers)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>set_scheme (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.set_scheme)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_clear_request (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_clear_request)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_clear_response (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_clear_response)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_clear_validate_param (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_clear_validate_param)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_set_request (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_set_request)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_set_response (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_set_response)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_json (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_json)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_operation_value (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_operation_value)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_param (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_param)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_resolved (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_resolved)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_spec (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_spec)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_url (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_url)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_validate_param (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_validate_param)

#### [module swagger-ui.plugins.SpecSelectors](#apidoc.module.swagger-ui.plugins.SpecSelectors)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>allowTryItOutFor ()](#apidoc.element.swagger-ui.plugins.SpecSelectors.allowTryItOutFor)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>basePath (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.basePath)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>canExecuteScheme (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.canExecuteScheme)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>consumes (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.consumes)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>contentTypeValues (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.contentTypeValues)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>definitions (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.definitions)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>externalDocs (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.externalDocs)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>findDefinition (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.findDefinition)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>getParameter (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.getParameter)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>hasHost (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.hasHost)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>host (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.host)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>info (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.info)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>lastError (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.lastError)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operationConsumes (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operationConsumes)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operationScheme (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operationScheme)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operations (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operations)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operationsWithRootInherited (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operationsWithRootInherited)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operationsWithTags (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operationsWithTags)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>parameterValues (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.parameterValues)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>parametersIncludeIn (e)](#apidoc.element.swagger-ui.plugins.SpecSelectors.parametersIncludeIn)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>parametersIncludeType (e)](#apidoc.element.swagger-ui.plugins.SpecSelectors.parametersIncludeType)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>paths (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.paths)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>produces (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.produces)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>requestFor (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.requestFor)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>requests (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.requests)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>responseFor (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.responseFor)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>responses (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.responses)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>schemes (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.schemes)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>security (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.security)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>securityDefinitions (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.securityDefinitions)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>semver (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.semver)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>spec (e)](#apidoc.element.swagger-ui.plugins.SpecSelectors.spec)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>specJson (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.specJson)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>specResolved (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.specResolved)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>specSource (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.specSource)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>specStr (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.specStr)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>tagDetails (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.tagDetails)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>taggedOperations (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.taggedOperations)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>tags (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.tags)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>url (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.url)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>validateBeforeExecute (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.validateBeforeExecute)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>version (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.version)

#### [module swagger-ui.plugins.SpecWrapActions](#apidoc.module.swagger-ui.plugins.SpecWrapActions)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecWrapActions.</span>executeRequest (e, t)](#apidoc.element.swagger-ui.plugins.SpecWrapActions.executeRequest)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecWrapActions.</span>updateJsonSpec (e, t)](#apidoc.element.swagger-ui.plugins.SpecWrapActions.updateJsonSpec)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecWrapActions.</span>updateSpec (e, t)](#apidoc.element.swagger-ui.plugins.SpecWrapActions.updateSpec)

#### [module swagger-ui.plugins.SplitPaneModeComponentsIndex](#apidoc.module.swagger-ui.plugins.SplitPaneModeComponentsIndex)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.SplitPaneModeComponentsIndex.</span>SplitPaneMode ()](#apidoc.element.swagger-ui.plugins.SplitPaneModeComponentsIndex.SplitPaneMode)

#### [module swagger-ui.plugins.ViewRootInjects](#apidoc.module.swagger-ui.plugins.ViewRootInjects)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ViewRootInjects.</span>getComponent (e, t, r, n, o)](#apidoc.element.swagger-ui.plugins.ViewRootInjects.getComponent)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ViewRootInjects.</span>makeMappedContainer (e, t, r, n, i, s)](#apidoc.element.swagger-ui.plugins.ViewRootInjects.makeMappedContainer)
1.  [function <span class="apidocSignatureSpan">swagger-ui.plugins.ViewRootInjects.</span>render (e, t, r, n, o)](#apidoc.element.swagger-ui.plugins.ViewRootInjects.render)

#### [module swagger-ui.presets](#apidoc.module.swagger-ui.presets)
1.  [function <span class="apidocSignatureSpan">swagger-ui.presets.</span>apis ()](#apidoc.element.swagger-ui.presets.apis)



# <a name="apidoc.module.swagger-ui"></a>[module swagger-ui](#apidoc.module.swagger-ui)



# <a name="apidoc.module.swagger-ui.plugins"></a>[module swagger-ui.plugins](#apidoc.module.swagger-ui.plugins)

#### <a name="apidoc.element.swagger-ui.plugins.AstIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AstIndex ()](#apidoc.element.swagger-ui.plugins.AstIndex)
- description and source-code
```javascript
AstIndex = function (){return{fn:{AST:u},components:{JumpToPath:s.default}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AstJumpToPath"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AstJumpToPath ()](#apidoc.element.swagger-ui.plugins.AstJumpToPath)
- description and source-code
```javascript
function t(){return o(this,t),a(this,(t.__proto__||Object.getPrototypeOf(t)).apply(this,arguments))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>AuthIndex ()](#apidoc.element.swagger-ui.plugins.AuthIndex)
- description and source-code
```javascript
AuthIndex = function (){return{statePlugins:{auth:{reducers:u.default,actions:s,selectors:l},spec:{wrapActions:f}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.DownloadUrl"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>DownloadUrl (e)](#apidoc.element.swagger-ui.plugins.DownloadUrl)
- description and source-code
```javascript
function n(e){var t=e.fn,r={download:function(e){return function(r){function n(t){return t instanceof Error||t.status>=400?(u.updateLoadingStatus
("failed"),o.newThrownErr(new Error(t.statusText+" "+e))):(u.updateLoadingStatus("success"),u.updateSpec(t.text),void u.updateUrl
(e))}var o=r.errActions,a=r.specSelectors,u=r.specActions,i=t.fetch;e=e||a.url(),u.updateLoadingStatus("loading"),i({url:e,loadSpec
:!0,headers:{Accept:"application/json"}}).then(n,n)}},updateLoadingStatus:function(e){var t=[null,"loading","failed","success","
failedConfig"];return t.indexOf(e)===-1&&console.error("Error: "+e+" is not one of "+JSON.stringify(t)),{type:"spec_update_loading_status
",payload:e}}},n={spec_update_loading_status:function(e,t){return"string"==typeof t.payload?e.set("loadingStatus",t.payload):e}},
u={loadingStatus:(0,o.createSelector)(function(e){return e||(0,a.Map)()},function(e){return e.get("loadingStatus")||null})};return
{statePlugins:{spec:{actions:r,reducers:n,selectors:u}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ErrErrorTransformersHook"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrErrorTransformersHook (e, t)](#apidoc.element.swagger-ui.plugins.ErrErrorTransformersHook)
- description and source-code
```javascript
function o(e, t){var r={jsSpec:t.specSelectors.specJson().toJS()},n=(0,i.default)(c,function(e,t){try{var n=t.transform(e,r);return
 n.filter(function(e){return!!e})}catch(t){return console.error("Transformer error:",t),e}},e);return n.filter(function(e){return
!!e}).map(function(e){return!e.get("line")&&e.get("path"),e})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ErrIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrIndex (e)](#apidoc.element.swagger-ui.plugins.ErrIndex)
- description and source-code
```javascript
ErrIndex = function (e){return{statePlugins:{err:{reducers:(0,u.default)(e),actions:s,selectors:l}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ErrReducers"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ErrReducers (e)](#apidoc.element.swagger-ui.plugins.ErrReducers)
- description and source-code
```javascript
ErrReducers = function (e){var t;return t={},o(t,a.NEW_THROWN_ERR,function(t,r){var n=r.payload,o=Object.assign(f,n,{type:"thrown"});return t.
update("errors",function(e){return(e||(0,s.List)()).push((0,s.fromJS)(o))}).update("errors",function(t){return(0,p.default)(t,e.
getSystem())})}),o(t,a.NEW_THROWN_ERR_BATCH,function(t,r){var n=r.payload;return n=n.map(function(e){return(0,s.fromJS)(Object.assign
(f,e,{type:"thrown"}))}),t.update("errors",function(e){return(e||(0,s.List)()).concat((0,s.fromJS)(n))}).update("errors",function
(t){return(0,p.default)(t,e.getSystem())})}),o(t,a.NEW_SPEC_ERR,function(t,r){var n=r.payload,o=(0,s.fromJS)(n);return o=o.set("
type","spec"),t.update("errors",function(e){return(e||(0,s.List)()).push((0,s.fromJS)(o)).sortBy(function(e){return e.get("line")})}).
update("errors",function(t){return(0,p.default)(t,e.getSystem())})}),o(t,a.NEW_AUTH_ERR,function(t,r){var n=r.payload,o=(0,s.fromJS
)(Object.assign({},n));return o=o.set("type","auth"),t.update("errors",function(e){return(e||(0,s.List)()).push((0,s.fromJS)(o))}).
update("errors",function(t){return(0,p.default)(t,e.getSystem())})}),o(t,a.CLEAR,function(e,t){var r=t.payload;if(r){var n=c.default
.fromJS((0,i.default)((e.get("errors")||(0,s.List)()).toJS(),r));return e.merge({errors:n})}}),t}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.LayoutIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>LayoutIndex ()](#apidoc.element.swagger-ui.plugins.LayoutIndex)
- description and source-code
```javascript
LayoutIndex = function (){return{statePlugins:{layout:{reducers:u.default,actions:s,selectors:l}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.LogsIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>LogsIndex (e)](#apidoc.element.swagger-ui.plugins.LogsIndex)
- description and source-code
```javascript
LogsIndex = function (e){function t(e){for(var t,r=arguments.length,n=Array(r>1?r-1:0),a=1;a<r;a++)n[a-1]=arguments[a];o(e)>=u&&(t=console)[
e].apply(t,n)}var r=e.configs,n={debug:0,info:1,log:2,warn:3,error:4},o=function(e){return n[e]||-1},a=r.logLevel,u=o(a);return
t.warn=t.bind(null,"warn"),t.error=t.bind(null,"error"),t.info=t.bind(null,"info"),t.debug=t.bind(null,"debug"),{rootInjects:{log
:t}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SamplesIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SamplesIndex ()](#apidoc.element.swagger-ui.plugins.SamplesIndex)
- description and source-code
```javascript
SamplesIndex = function (){return{fn:a}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SpecIndex ()](#apidoc.element.swagger-ui.plugins.SpecIndex)
- description and source-code
```javascript
SpecIndex = function (){return{statePlugins:{spec:{wrapActions:f,reducers:u.default,actions:s,selectors:l}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SplitPaneModeComponentsSplitPaneMode"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SplitPaneModeComponentsSplitPaneMode ()](#apidoc.element.swagger-ui.plugins.SplitPaneModeComponentsSplitPaneMode)
- description and source-code
```javascript
function t(){var e,r,n,u;o(this,t);for(var i=arguments.length,s=Array(i),c=0;c<i;c++)s[c]=arguments[c];return r=n=a(this,(e=t.__proto__
||Object.getPrototypeOf(t)).call.apply(e,[this].concat(s))),n.onDragFinished=function(){var e=n.props,t=e.threshold,r=e.layoutActions
,o=n.refs.splitPane.state,a=o.position,u=o.draggedSize;n.draggedSize=u;var i=a<=t,s=u<=t;r.changeMode(f,i?y:s?d:h)},n.sizeFromMode
=function(e,t){return e===d?(n.draggedSize=null,"0px"):e===y?(n.draggedSize=null,"100%"):n.draggedSize||t},u=r,a(n,u)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SplitPaneModeIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SplitPaneModeIndex ()](#apidoc.element.swagger-ui.plugins.SplitPaneModeIndex)
- description and source-code
```javascript
function o(){return{components:u}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SwaggerJsIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>SwaggerJsIndex (e)](#apidoc.element.swagger-ui.plugins.SwaggerJsIndex)
- description and source-code
```javascript
SwaggerJsIndex = function (e){var t=e.configs;return{fn:{fetch:a.default.makeHttp(t.preFetch,t.postFetch),buildRequest:a.default.buildRequest,execute
:a.default.execute,resolve:a.default.resolve,serializeRes:a.default.serializeRes}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.UtilIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>UtilIndex ()](#apidoc.element.swagger-ui.plugins.UtilIndex)
- description and source-code
```javascript
UtilIndex = function (){return{fn:{shallowEqualKeys:n.shallowEqualKeys,transformPathToArray:o.transformPathToArray}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ViewIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.</span>ViewIndex (e)](#apidoc.element.swagger-ui.plugins.ViewIndex)
- description and source-code
```javascript
ViewIndex = function (e){var t=e.getComponents,r=e.getStore,n=e.getSystem,o=a.getComponent,i=a.render,s=a.makeMappedContainer,c=(0,u.memoize
)(o.bind(null,n,r,t)),l=(0,u.memoize)(s.bind(null,n,r,c,t));return{rootInjects:{getComponent:c,makeMappedContainer:l,render:i.bind
(null,n,r,o,t)}}}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.All"></a>[module swagger-ui.plugins.All](#apidoc.module.swagger-ui.plugins.All)

#### <a name="apidoc.element.swagger-ui.plugins.All.AstIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AstIndex ()](#apidoc.element.swagger-ui.plugins.All.AstIndex)
- description and source-code
```javascript
AstIndex = function (){return{fn:{AST:u},components:{JumpToPath:s.default}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.AstJumpToPath"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AstJumpToPath ()](#apidoc.element.swagger-ui.plugins.All.AstJumpToPath)
- description and source-code
```javascript
function t(){return o(this,t),a(this,(t.__proto__||Object.getPrototypeOf(t)).apply(this,arguments))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.AuthIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>AuthIndex ()](#apidoc.element.swagger-ui.plugins.All.AuthIndex)
- description and source-code
```javascript
AuthIndex = function (){return{statePlugins:{auth:{reducers:u.default,actions:s,selectors:l},spec:{wrapActions:f}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.DownloadUrl"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>DownloadUrl (e)](#apidoc.element.swagger-ui.plugins.All.DownloadUrl)
- description and source-code
```javascript
function n(e){var t=e.fn,r={download:function(e){return function(r){function n(t){return t instanceof Error||t.status>=400?(u.updateLoadingStatus
("failed"),o.newThrownErr(new Error(t.statusText+" "+e))):(u.updateLoadingStatus("success"),u.updateSpec(t.text),void u.updateUrl
(e))}var o=r.errActions,a=r.specSelectors,u=r.specActions,i=t.fetch;e=e||a.url(),u.updateLoadingStatus("loading"),i({url:e,loadSpec
:!0,headers:{Accept:"application/json"}}).then(n,n)}},updateLoadingStatus:function(e){var t=[null,"loading","failed","success","
failedConfig"];return t.indexOf(e)===-1&&console.error("Error: "+e+" is not one of "+JSON.stringify(t)),{type:"spec_update_loading_status
",payload:e}}},n={spec_update_loading_status:function(e,t){return"string"==typeof t.payload?e.set("loadingStatus",t.payload):e}},
u={loadingStatus:(0,o.createSelector)(function(e){return e||(0,a.Map)()},function(e){return e.get("loadingStatus")||null})};return
{statePlugins:{spec:{actions:r,reducers:n,selectors:u}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.ErrErrorTransformersHook"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrErrorTransformersHook (e, t)](#apidoc.element.swagger-ui.plugins.All.ErrErrorTransformersHook)
- description and source-code
```javascript
function o(e, t){var r={jsSpec:t.specSelectors.specJson().toJS()},n=(0,i.default)(c,function(e,t){try{var n=t.transform(e,r);return
 n.filter(function(e){return!!e})}catch(t){return console.error("Transformer error:",t),e}},e);return n.filter(function(e){return
!!e}).map(function(e){return!e.get("line")&&e.get("path"),e})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.ErrIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrIndex (e)](#apidoc.element.swagger-ui.plugins.All.ErrIndex)
- description and source-code
```javascript
ErrIndex = function (e){return{statePlugins:{err:{reducers:(0,u.default)(e),actions:s,selectors:l}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.ErrReducers"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ErrReducers (e)](#apidoc.element.swagger-ui.plugins.All.ErrReducers)
- description and source-code
```javascript
ErrReducers = function (e){var t;return t={},o(t,a.NEW_THROWN_ERR,function(t,r){var n=r.payload,o=Object.assign(f,n,{type:"thrown"});return t.
update("errors",function(e){return(e||(0,s.List)()).push((0,s.fromJS)(o))}).update("errors",function(t){return(0,p.default)(t,e.
getSystem())})}),o(t,a.NEW_THROWN_ERR_BATCH,function(t,r){var n=r.payload;return n=n.map(function(e){return(0,s.fromJS)(Object.assign
(f,e,{type:"thrown"}))}),t.update("errors",function(e){return(e||(0,s.List)()).concat((0,s.fromJS)(n))}).update("errors",function
(t){return(0,p.default)(t,e.getSystem())})}),o(t,a.NEW_SPEC_ERR,function(t,r){var n=r.payload,o=(0,s.fromJS)(n);return o=o.set("
type","spec"),t.update("errors",function(e){return(e||(0,s.List)()).push((0,s.fromJS)(o)).sortBy(function(e){return e.get("line")})}).
update("errors",function(t){return(0,p.default)(t,e.getSystem())})}),o(t,a.NEW_AUTH_ERR,function(t,r){var n=r.payload,o=(0,s.fromJS
)(Object.assign({},n));return o=o.set("type","auth"),t.update("errors",function(e){return(e||(0,s.List)()).push((0,s.fromJS)(o))}).
update("errors",function(t){return(0,p.default)(t,e.getSystem())})}),o(t,a.CLEAR,function(e,t){var r=t.payload;if(r){var n=c.default
.fromJS((0,i.default)((e.get("errors")||(0,s.List)()).toJS(),r));return e.merge({errors:n})}}),t}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.LayoutIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>LayoutIndex ()](#apidoc.element.swagger-ui.plugins.All.LayoutIndex)
- description and source-code
```javascript
LayoutIndex = function (){return{statePlugins:{layout:{reducers:u.default,actions:s,selectors:l}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.LogsIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>LogsIndex (e)](#apidoc.element.swagger-ui.plugins.All.LogsIndex)
- description and source-code
```javascript
LogsIndex = function (e){function t(e){for(var t,r=arguments.length,n=Array(r>1?r-1:0),a=1;a<r;a++)n[a-1]=arguments[a];o(e)>=u&&(t=console)[
e].apply(t,n)}var r=e.configs,n={debug:0,info:1,log:2,warn:3,error:4},o=function(e){return n[e]||-1},a=r.logLevel,u=o(a);return
t.warn=t.bind(null,"warn"),t.error=t.bind(null,"error"),t.info=t.bind(null,"info"),t.debug=t.bind(null,"debug"),{rootInjects:{log
:t}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.SamplesIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SamplesIndex ()](#apidoc.element.swagger-ui.plugins.All.SamplesIndex)
- description and source-code
```javascript
SamplesIndex = function (){return{fn:a}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.SpecIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SpecIndex ()](#apidoc.element.swagger-ui.plugins.All.SpecIndex)
- description and source-code
```javascript
SpecIndex = function (){return{statePlugins:{spec:{wrapActions:f,reducers:u.default,actions:s,selectors:l}}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.SplitPaneModeComponentsSplitPaneMode"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SplitPaneModeComponentsSplitPaneMode ()](#apidoc.element.swagger-ui.plugins.All.SplitPaneModeComponentsSplitPaneMode)
- description and source-code
```javascript
function t(){var e,r,n,u;o(this,t);for(var i=arguments.length,s=Array(i),c=0;c<i;c++)s[c]=arguments[c];return r=n=a(this,(e=t.__proto__
||Object.getPrototypeOf(t)).call.apply(e,[this].concat(s))),n.onDragFinished=function(){var e=n.props,t=e.threshold,r=e.layoutActions
,o=n.refs.splitPane.state,a=o.position,u=o.draggedSize;n.draggedSize=u;var i=a<=t,s=u<=t;r.changeMode(f,i?y:s?d:h)},n.sizeFromMode
=function(e,t){return e===d?(n.draggedSize=null,"0px"):e===y?(n.draggedSize=null,"100%"):n.draggedSize||t},u=r,a(n,u)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.SplitPaneModeIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SplitPaneModeIndex ()](#apidoc.element.swagger-ui.plugins.All.SplitPaneModeIndex)
- description and source-code
```javascript
function o(){return{components:u}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.SwaggerJsIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>SwaggerJsIndex (e)](#apidoc.element.swagger-ui.plugins.All.SwaggerJsIndex)
- description and source-code
```javascript
SwaggerJsIndex = function (e){var t=e.configs;return{fn:{fetch:a.default.makeHttp(t.preFetch,t.postFetch),buildRequest:a.default.buildRequest,execute
:a.default.execute,resolve:a.default.resolve,serializeRes:a.default.serializeRes}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.UtilIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>UtilIndex ()](#apidoc.element.swagger-ui.plugins.All.UtilIndex)
- description and source-code
```javascript
UtilIndex = function (){return{fn:{shallowEqualKeys:n.shallowEqualKeys,transformPathToArray:o.transformPathToArray}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.All.ViewIndex"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.All.</span>ViewIndex (e)](#apidoc.element.swagger-ui.plugins.All.ViewIndex)
- description and source-code
```javascript
ViewIndex = function (e){var t=e.getComponents,r=e.getStore,n=e.getSystem,o=a.getComponent,i=a.render,s=a.makeMappedContainer,c=(0,u.memoize
)(o.bind(null,n,r,t)),l=(0,u.memoize)(s.bind(null,n,r,c,t));return{rootInjects:{getComponent:c,makeMappedContainer:l,render:i.bind
(null,n,r,o,t)}}}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.AstAst"></a>[module swagger-ui.plugins.AstAst](#apidoc.module.swagger-ui.plugins.AstAst)

#### <a name="apidoc.element.swagger-ui.plugins.AstAst.getLineNumberForPath"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>getLineNumberForPath (e, t)](#apidoc.element.swagger-ui.plugins.AstAst.getLineNumberForPath)
- description and source-code
```javascript
function o(e, t){function r(e,t,o){if(!e)return o&&o.start_mark?o.start_mark.line:0;if(t.length&&e.tag===v)for(n=0;n<e.value.length
;n++){var a=e.value[n],u=a[0],i=a[1];if(u.value===t[0])return r(i,t.slice(1),e);if(u.value===t[0].replace(/\[.*/,"")){var s=parseInt(t[0].match(/\[(.*)\]/)[1]);if(1===i.value.length&&0!==s&&s)var c=(0,y.default)(i.value[0],{value:s.toString()});else var c=i.value[s];return r(c,t.slice(1),i.value)}}if(t.length&&e.tag===b){var l=e.value[t[0]];if(l&&l.tag)return r(l,t.slice(1),e.value)}return e.tag!==v||Array.isArray(o)?e.start_mark.line+1:e.start_mark.line}if("string"!=typeof e)throw new TypeError("yaml should be a string");if(!(0,f.default)(t))throw new TypeError("path should be an array of strings");var n=0,o=m(e);return r(o,t)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AstAst.getLineNumberForPathAsync"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>getLineNumberForPathAsync ()](#apidoc.element.swagger-ui.plugins.AstAst.getLineNumberForPathAsync)
- description and source-code
```javascript
getLineNumberForPathAsync = function (){for(var t=arguments.length,r=Array(t),n=0;n<t;n++)r[n]=arguments[n];return new Promise(function(t){return t(e.apply(
void 0,r))})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AstAst.pathForPosition"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>pathForPosition (e, t)](#apidoc.element.swagger-ui.plugins.AstAst.pathForPosition)
- description and source-code
```javascript
function u(e, t){function r(e){function n(e){return e.start_mark.line===e.end_mark.line?t.line===e.start_mark.line&&e.start_mark.
column<=t.column&&e.end_mark.column>=t.column:t.line===e.start_mark.line?t.column>=e.start_mark.column:t.line===e.end_mark.line?
t.column<=e.end_mark.column:e.start_mark.line<t.line&&e.end_mark.line>t.line}var a=0;if(!e||[v,b].indexOf(e.tag)===-1)return o;if
(e.tag===v)for(a=0;a<e.value.length;a++){var u=e.value[a],i=u[0],s=u[1];if(n(i))return o;if(n(s))return o.push(i.value),r(s)}if(
e.tag===b)for(a=0;a<e.value.length;a++){var c=e.value[a];if(n(c))return o.push(a.toString()),r(c)}return o}if("string"!=typeof e
)throw new TypeError("yaml should be a string");if("object"!==("undefined"==typeof t?"undefined":s(t))||"number"!=typeof t.line||"
number"!=typeof t.column)throw new TypeError("position should be an object with line and column properties");try{var n=m(e)}catch
(r){return console.error("Error composing AST",r),console.error("Problem area:\n",e.split("\n").slice(t.line-5,t.line+5).join("\n")),null}var o=[];return r(n)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AstAst.pathForPositionAsync"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>pathForPositionAsync ()](#apidoc.element.swagger-ui.plugins.AstAst.pathForPositionAsync)
- description and source-code
```javascript
pathForPositionAsync = function (){for(var t=arguments.length,r=Array(t),n=0;n<t;n++)r[n]=arguments[n];return new Promise(function(t){return t(e.apply(
void 0,r))})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AstAst.positionRangeForPath"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>positionRangeForPath (e, t)](#apidoc.element.swagger-ui.plugins.AstAst.positionRangeForPath)
- description and source-code
```javascript
function a(e, t){function r(e){if(e.tag===v)for(o=0;o<e.value.length;o++){var a=e.value[o],u=a[0],i=a[1];if(u.value===t[0])return
 t.shift(),r(i)}if(e.tag===b){var s=e.value[t[0]];if(s&&s.tag)return t.shift(),r(s)}return t.length?n:{start:{line:e.start_mark.
line,column:e.start_mark.column},end:{line:e.end_mark.line,column:e.end_mark.column}}}if("string"!=typeof e)throw new TypeError("
yaml should be a string");if(!(0,f.default)(t))throw new TypeError("path should be an array of strings");var n={start:{line:-1,column
:-1},end:{line:-1,column:-1}},o=0,a=m(e);return r(a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AstAst.positionRangeForPathAsync"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AstAst.</span>positionRangeForPathAsync ()](#apidoc.element.swagger-ui.plugins.AstAst.positionRangeForPathAsync)
- description and source-code
```javascript
positionRangeForPathAsync = function (){for(var t=arguments.length,r=Array(t),n=0;n<t;n++)r[n]=arguments[n];return new Promise(function(t){return t(e.apply(
void 0,r))})}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.AuthActions"></a>[module swagger-ui.plugins.AuthActions](#apidoc.module.swagger-ui.plugins.AuthActions)

#### <a name="apidoc.element.swagger-ui.plugins.AuthActions.authorize"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>authorize (e)](#apidoc.element.swagger-ui.plugins.AuthActions.authorize)
- description and source-code
```javascript
function a(e){return{type:d,payload:e}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthActions.authorizeOauth2"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>authorizeOauth2 (e)](#apidoc.element.swagger-ui.plugins.AuthActions.authorizeOauth2)
- description and source-code
```javascript
function i(e){return{type:h,payload:e}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthActions.authorizePassword"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>authorizePassword (e)](#apidoc.element.swagger-ui.plugins.AuthActions.authorizePassword)
- description and source-code
```javascript
authorizePassword = function (e){return function(t){var r=t.fn,n=t.authActions,o=t.errActions,a=e.schema,u=e.name,i=e.username,s=e.password,c=e.passwordType
,l=e.clientId,f=e.clientSecret,d={url:a.get("tokenUrl"),method:"post",headers:{"content-type":"application/x-www-form-urlencoded
"},query:{grant_type:"password",username:i,password:s}};return"basic"===c?d.headers.authorization="Basic "+(0,p.default)(l+":"+f
):"request"===c&&(d.query=Object.assign(d.query,{client_id:l,client_secret:f})),r.fetch(d).then(function(t){var r=JSON.parse(t.data
),a=r&&(r.error||""),i=r&&(r.parseError||"");return t.ok?a||i?void o.newAuthErr({authId:u,level:"error",source:"auth",message:JSON
.stringify(r)}):void n.authorizeOauth2({auth:e,token:r}):void o.newAuthErr({authId:u,level:"error",source:"auth",message:t.statusText
})}).catch(function(e){o.newAuthErr(e)})}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthActions.logout"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>logout (e)](#apidoc.element.swagger-ui.plugins.AuthActions.logout)
- description and source-code
```javascript
function u(e){return{type:y,payload:e}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthActions.preAuthorizeOauth2"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>preAuthorizeOauth2 (e)](#apidoc.element.swagger-ui.plugins.AuthActions.preAuthorizeOauth2)
- description and source-code
```javascript
preAuthorizeOauth2 = function (e){return function(t){var r=t.authActions,n=t.errActions,o=e.auth,a=e.token,u=e.isValid,i=o.schema,s=o.name,l=i.get("flow
");return delete c.default.swaggerUIRedirectOauth2,"accessCode"===l||u||n.newAuthErr({authId:s,source:"auth",level:"warning",message
:"Authorization may be unsafe, passed state was changed in server Passed state wasn't returned from auth server"}),a.error?void
n.newAuthErr({authId:s,source:"auth",level:"error",message:JSON.stringify(a)}):void r.authorizeOauth2({auth:o,token:a})}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthActions.showDefinitions"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthActions.</span>showDefinitions (e)](#apidoc.element.swagger-ui.plugins.AuthActions.showDefinitions)
- description and source-code
```javascript
function o(e){return{type:f,payload:e}}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.AuthReducers"></a>[module swagger-ui.plugins.AuthReducers](#apidoc.module.swagger-ui.plugins.AuthReducers)

#### <a name="apidoc.element.swagger-ui.plugins.AuthReducers.authorize"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthReducers.</span>authorize (e, t)](#apidoc.element.swagger-ui.plugins.AuthReducers.authorize)
- description and source-code
```javascript
authorize = function (e, t){var r=t.payload,n=(0,i.fromJS)(r),o=e.get("authorized")||(0,i.Map)();return n.entrySeq().forEach(function(e){var
t=u(e,2),r=t[0],n=t[1],a=n.getIn(["schema","type"]);if("apiKey"===a)o=o.set(r,n);else if("basic"===a){var i=n.getIn(["value","username
"]),s=n.getIn(["value","password"]);o=o.setIn([r,"value"],{username:i,header:"Basic "+(0,c.default)(i+":"+s)}),o=o.setIn([r,"schema
"],n.get("schema"))}}),e.set("authorized",o)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthReducers.authorize_oauth2"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthReducers.</span>authorize_oauth2 (e, t)](#apidoc.element.swagger-ui.plugins.AuthReducers.authorize_oauth2)
- description and source-code
```javascript
authorize_oauth2 = function (e, t){var r=t.payload,n=r.auth,o=r.token,a=void 0;return n.token=o,a=(0,i.fromJS)(n),e.setIn(["authorized",a.get("name")],
a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthReducers.logout"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthReducers.</span>logout (e, t)](#apidoc.element.swagger-ui.plugins.AuthReducers.logout)
- description and source-code
```javascript
logout = function (e, t){var r=t.payload,n=e.get("authorized").withMutations(function(e){r.forEach(function(t){e.delete(t)})});return e.set
("authorized",n)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthReducers.show_popup"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthReducers.</span>show_popup (e, t)](#apidoc.element.swagger-ui.plugins.AuthReducers.show_popup)
- description and source-code
```javascript
show_popup = function (e, t){var r=t.payload;return e.set("showDefinitions",r)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.AuthSelectors"></a>[module swagger-ui.plugins.AuthSelectors](#apidoc.module.swagger-ui.plugins.AuthSelectors)

#### <a name="apidoc.element.swagger-ui.plugins.AuthSelectors.authorized"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>authorized (state, props)](#apidoc.element.swagger-ui.plugins.AuthSelectors.authorized)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthSelectors.definitionsToAuthorize"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>definitionsToAuthorize (state, props)](#apidoc.element.swagger-ui.plugins.AuthSelectors.definitionsToAuthorize)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthSelectors.getDefinitionsByNames"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>getDefinitionsByNames (e, t)](#apidoc.element.swagger-ui.plugins.AuthSelectors.getDefinitionsByNames)
- description and source-code
```javascript
getDefinitionsByNames = function (e, t){return function(e){var r=e.specSelectors,o=r.securityDefinitions(),u=(0,a.List)();return t.valueSeq().forEach(function
(e){var t=(0,a.Map)();e.entrySeq().forEach(function(e){var r=n(e,2),a=r[0],u=r[1],i=o.get(a),s=void 0;"oauth2"===i.get("type")&&
u.size&&(s=i.get("scopes"),s.keySeq().forEach(function(e){u.contains(e)||(s=s.delete(e))}),i=i.set("allowedScopes",s)),t=t.set(a
,i)}),u=u.push(t)}),u}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthSelectors.isAuthorized"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>isAuthorized (e, t)](#apidoc.element.swagger-ui.plugins.AuthSelectors.isAuthorized)
- description and source-code
```javascript
isAuthorized = function (e, t){return function(e){var r=e.authSelectors,n=r.authorized();return!!t.toJS().filter(function(e){var t=!0;return Object
.keys(e).map(function(e){return!t||!!n.get(e)}).indexOf(!1)===-1}).length}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.AuthSelectors.shownDefinitions"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSelectors.</span>shownDefinitions (state, props)](#apidoc.element.swagger-ui.plugins.AuthSelectors.shownDefinitions)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.AuthSpecWrapActions"></a>[module swagger-ui.plugins.AuthSpecWrapActions](#apidoc.module.swagger-ui.plugins.AuthSpecWrapActions)

#### <a name="apidoc.element.swagger-ui.plugins.AuthSpecWrapActions.execute"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.AuthSpecWrapActions.</span>execute (e, t)](#apidoc.element.swagger-ui.plugins.AuthSpecWrapActions.execute)
- description and source-code
```javascript
execute = function (e, t){var n=t.authSelectors,o=t.specSelectors;return function(t){var a=t.path,u=t.method,i=t.operation,s=t.extras,c={authorized
:n.authorized()&&n.authorized().toJS(),definitions:o.securityDefinitions()&&o.securityDefinitions().toJS(),specSecurity:o.security
()&&o.security().toJS()};return e(r({path:a,method:u,operation:i,securities:c},s))}}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.ErrActions"></a>[module swagger-ui.plugins.ErrActions](#apidoc.module.swagger-ui.plugins.ErrActions)

#### <a name="apidoc.element.swagger-ui.plugins.ErrActions.clear"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>clear ()](#apidoc.element.swagger-ui.plugins.ErrActions.clear)
- description and source-code
```javascript
function s(){var e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:{};return{type:h,payload:e}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ErrActions.newAuthErr"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>newAuthErr (e)](#apidoc.element.swagger-ui.plugins.ErrActions.newAuthErr)
- description and source-code
```javascript
function i(e){return{type:y,payload:e}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ErrActions.newSpecErr"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>newSpecErr (e)](#apidoc.element.swagger-ui.plugins.ErrActions.newSpecErr)
- description and source-code
```javascript
function u(e){return{type:d,payload:e}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ErrActions.newThrownErr"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>newThrownErr (e, t)](#apidoc.element.swagger-ui.plugins.ErrActions.newThrownErr)
- description and source-code
```javascript
function o(e, t){return{type:p,payload:{action:t,error:(0,l.default)(e)}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ErrActions.newThrownErrBatch"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrActions.</span>newThrownErrBatch (e)](#apidoc.element.swagger-ui.plugins.ErrActions.newThrownErrBatch)
- description and source-code
```javascript
function a(e){return{type:f,payload:e}}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType"></a>[module swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType](#apidoc.module.swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType)

#### <a name="apidoc.element.swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType.transform"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType.</span>transform (e)](#apidoc.element.swagger-ui.plugins.ErrErrorTransformersTransformersNotOfType.transform)
- description and source-code
```javascript
function r(e){return e.map(function(e){var t="is not of a type(s)",r=e.get("message").indexOf(t);if(r>-1){var o=e.get("message").
slice(r+t.length).split(",");return e.set("message",e.get("message").slice(0,r)+n(o))}return e})}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof"></a>[module swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof](#apidoc.module.swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof)

#### <a name="apidoc.element.swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof.transform"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof.</span>transform (e, t)](#apidoc.element.swagger-ui.plugins.ErrErrorTransformersTransformersParameterOneof.transform)
- description and source-code
```javascript
function o(e, t){t.jsSpec;return e}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance"></a>[module swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance](#apidoc.module.swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance)

#### <a name="apidoc.element.swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance.transform"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance.</span>transform (e)](#apidoc.element.swagger-ui.plugins.ErrErrorTransformersTransformersStripInstance.transform)
- description and source-code
```javascript
function r(e){return e.map(function(e){return e.set("message",n(e.get("message"),"instance."))})}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.ErrSelectors"></a>[module swagger-ui.plugins.ErrSelectors](#apidoc.module.swagger-ui.plugins.ErrSelectors)

#### <a name="apidoc.element.swagger-ui.plugins.ErrSelectors.allErrors"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrSelectors.</span>allErrors (state, props)](#apidoc.element.swagger-ui.plugins.ErrSelectors.allErrors)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ErrSelectors.lastError"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ErrSelectors.</span>lastError (state, props)](#apidoc.element.swagger-ui.plugins.ErrSelectors.lastError)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.LayoutActions"></a>[module swagger-ui.plugins.LayoutActions](#apidoc.module.swagger-ui.plugins.LayoutActions)

#### <a name="apidoc.element.swagger-ui.plugins.LayoutActions.changeMode"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutActions.</span>changeMode (e)](#apidoc.element.swagger-ui.plugins.LayoutActions.changeMode)
- description and source-code
```javascript
function a(e){var t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:"";return e=(0,u.normalizeArray)(e),{type:s,payload:{
thing:e,mode:t}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.LayoutActions.show"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutActions.</span>show (e)](#apidoc.element.swagger-ui.plugins.LayoutActions.show)
- description and source-code
```javascript
function o(e){var t=!(arguments.length>1&&void 0!==arguments[1])||arguments[1];return e=(0,u.normalizeArray)(e),{type:c,payload:{
thing:e,shown:t}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.LayoutActions.updateLayout"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutActions.</span>updateLayout (e)](#apidoc.element.swagger-ui.plugins.LayoutActions.updateLayout)
- description and source-code
```javascript
function n(e){return{type:i,payload:e}}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.LayoutReducers"></a>[module swagger-ui.plugins.LayoutReducers](#apidoc.module.swagger-ui.plugins.LayoutReducers)

#### <a name="apidoc.element.swagger-ui.plugins.LayoutReducers.layout_show"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutReducers.</span>layout_show (e, t)](#apidoc.element.swagger-ui.plugins.LayoutReducers.layout_show)
- description and source-code
```javascript
layout_show = function (e, t){var r=t.payload.thing,n=t.payload.shown;return e.setIn(["shown"].concat(r),n)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.LayoutReducers.layout_update_layout"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutReducers.</span>layout_update_layout (e, t)](#apidoc.element.swagger-ui.plugins.LayoutReducers.layout_update_layout)
- description and source-code
```javascript
layout_update_layout = function (e, t){return e.set("layout",t.payload)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.LayoutReducers.layout_update_mode"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutReducers.</span>layout_update_mode (e, t)](#apidoc.element.swagger-ui.plugins.LayoutReducers.layout_update_mode)
- description and source-code
```javascript
layout_update_mode = function (e, t){var r=t.payload.thing,n=t.payload.mode;return e.setIn(["modes"].concat(r),(n||"")+"")}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.LayoutSelectors"></a>[module swagger-ui.plugins.LayoutSelectors](#apidoc.module.swagger-ui.plugins.LayoutSelectors)

#### <a name="apidoc.element.swagger-ui.plugins.LayoutSelectors.current"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutSelectors.</span>current (e)](#apidoc.element.swagger-ui.plugins.LayoutSelectors.current)
- description and source-code
```javascript
current = function (e){return e.get("layout")}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.LayoutSelectors.isShown"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutSelectors.</span>isShown (e, t, r)](#apidoc.element.swagger-ui.plugins.LayoutSelectors.isShown)
- description and source-code
```javascript
isShown = function (e, t, r){return t=(0,a.normalizeArray)(t),Boolean(e.getIn(["shown"].concat(n(t)),r))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.LayoutSelectors.showSummary"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutSelectors.</span>showSummary (state, props)](#apidoc.element.swagger-ui.plugins.LayoutSelectors.showSummary)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.LayoutSelectors.whatMode"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.LayoutSelectors.</span>whatMode (e, t)](#apidoc.element.swagger-ui.plugins.LayoutSelectors.whatMode)
- description and source-code
```javascript
whatMode = function (e, t){var r=arguments.length>2&&void 0!==arguments[2]?arguments[2]:"";return t=(0,a.normalizeArray)(t),e.getIn(["modes"].
concat(n(t)),r)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.SamplesFn"></a>[module swagger-ui.plugins.SamplesFn](#apidoc.module.swagger-ui.plugins.SamplesFn)

#### <a name="apidoc.element.swagger-ui.plugins.SamplesFn.createXMLExample"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>createXMLExample (e, t)](#apidoc.element.swagger-ui.plugins.SamplesFn.createXMLExample)
- description and source-code
```javascript
function o(e, t){var r=d(e,t);if(r)return(0,i.default)(r,{declaration:!0,indent:"\t"})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SamplesFn.inferSchema"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>inferSchema (e)](#apidoc.element.swagger-ui.plugins.SamplesFn.inferSchema)
- description and source-code
```javascript
inferSchema = function (e){return e.schema&&(e=e.schema),e.properties&&(e.type="object"),e}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SamplesFn.memoizedCreateXMLExample"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>memoizedCreateXMLExample (arg)](#apidoc.element.swagger-ui.plugins.SamplesFn.memoizedCreateXMLExample)
- description and source-code
```javascript
memoizedCreateXMLExample = function (arg) {
			var id, result, args = arguments;
			if (resolve) args = resolve(args);
			id = get(args);
			if (id !== null) {
				if (hasOwnProperty.call(cache, id)) {
					if (getListeners) conf.emit('get', id, args, this);
					return cache[id];
				}
			}
			if (args.length === 1) result = call.call(original, this, args[0]);
			else result = apply.call(original, this, args);
			if (id === null) {
				id = get(args);
				if (id !== null) throw customError("Circular invocation", 'CIRCULAR_INVOCATION');
				id = set(args);
			} else if (hasOwnProperty.call(cache, id)) {
				throw customError("Circular invocation", 'CIRCULAR_INVOCATION');
			}
			cache[id] = result;
			if (setListeners) conf.emit('set', id, null, result);
			return result;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SamplesFn.memoizedSampleFromSchema"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>memoizedSampleFromSchema (arg)](#apidoc.element.swagger-ui.plugins.SamplesFn.memoizedSampleFromSchema)
- description and source-code
```javascript
memoizedSampleFromSchema = function (arg) {
			var id, result, args = arguments;
			if (resolve) args = resolve(args);
			id = get(args);
			if (id !== null) {
				if (hasOwnProperty.call(cache, id)) {
					if (getListeners) conf.emit('get', id, args, this);
					return cache[id];
				}
			}
			if (args.length === 1) result = call.call(original, this, args[0]);
			else result = apply.call(original, this, args);
			if (id === null) {
				id = get(args);
				if (id !== null) throw customError("Circular invocation", 'CIRCULAR_INVOCATION');
				id = set(args);
			} else if (hasOwnProperty.call(cache, id)) {
				throw customError("Circular invocation", 'CIRCULAR_INVOCATION');
			}
			cache[id] = result;
			if (setListeners) conf.emit('set', id, null, result);
			return result;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SamplesFn.sampleFromSchema"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>sampleFromSchema (t)](#apidoc.element.swagger-ui.plugins.SamplesFn.sampleFromSchema)
- description and source-code
```javascript
function e(t){var r=arguments.length>1&&void 0!==arguments[1]?arguments[1]:{},n=(0,a.objectify)(t),o=n.type,u=n.example,i=n.properties
,s=n.additionalProperties,c=n.items,l=r.includeReadOnly;if(void 0!==u)return u;if(!o)if(i)o="object";else{if(!c)return;o="array"}
if("object"===o){var f=(0,a.objectify)(i),d={};for(var y in f)f[y].readOnly&&!l||(d[y]=e(f[y]));if(s===!0)d.additionalProp1={};else
 if(s)for(var h=(0,a.objectify)(s),m=e(h),v=1;v<4;v++)d["additionalProp"+v]=m;return d}return"array"===o?[e(c)]:t.enum?t.default
?t.default:(0,a.normalizeArray)(t.enum)[0]:p(t)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SamplesFn.sampleXmlFromSchema"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SamplesFn.</span>sampleXmlFromSchema (t)](#apidoc.element.swagger-ui.plugins.SamplesFn.sampleXmlFromSchema)
- description and source-code
```javascript
function e(t){var r=arguments.length>1&&void 0!==arguments[1]?arguments[1]:{},n=(0,a.objectify)(t),o=n.type,u=n.properties,i=n.additionalProperties
,s=n.items,c=n.example,l=r.includeReadOnly,f=n.default,d={},y={},h=t.xml,m=h.name,v=h.prefix,b=h.namespace,g=n.enum,_=void 0,E=void
 0;if(!o)if(u||i)o="object";else{if(!s)return;o="array"}if(m=m||"notagname",_=(v?v+":":"")+m,b){var j=v?"xmlns:"+v:"xmlns";y[j]=
b}if("array"===o&&s){if(s.xml=s.xml||h||{},s.xml.name=s.xml.name||h.name,h.wrapped)return d[_]=[],Array.isArray(c)?c.forEach(function
(t){s.example=t,d[_].push(e(s,r))}):Array.isArray(f)?f.forEach(function(t){s.default=t,d[_].push(e(s,r))}):d[_]=[e(s,r)],y&&d[_].
push({_attr:y}),d;var w=[];return Array.isArray(c)?(c.forEach(function(t){s.example=t,w.push(e(s,r))}),w):Array.isArray(f)?(f.forEach
(function(t){s.default=t,w.push(e(s,r))}),w):e(s,r)}if("object"===o){var O=(0,a.objectify)(u);d[_]=[],c=c||{};for(var P in O)if(!
O[P].readOnly||l)if(O[P].xml=O[P].xml||{},O[P].xml.attribute){var T=Array.isArray(O[P].enum)&&O[P].enum[0],S=O[P].example,x=O[P].
default;y[O[P].xml.name||P]=void 0!==S&&S||void 0!==c[P]&&c[P]||void 0!==x&&x||T||p(O[P])}else{O[P].xml.name=O[P].xml.name||P,O[
P].example=void 0!==O[P].example?O[P].example:c[P];var C=e(O[P]);Array.isArray(C)?d[_]=d[_].concat(C):d[_].push(C)}return i===!0
?d[_].push({additionalProp:"Anything can be here"}):i&&d[_].push({additionalProp:p(i)}),y&&d[_].push({_attr:y}),d}return E=void
0!==c?c:void 0!==f?f:Array.isArray(g)?g[0]:p(t),d[_]=y?[{_attr:y},E]:E,d}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.SpecActions"></a>[module swagger-ui.plugins.SpecActions](#apidoc.module.swagger-ui.plugins.SpecActions)

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.changeConsumesValue"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>changeConsumesValue (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.changeConsumesValue)
- description and source-code
```javascript
function f(e, t){return{type:M,payload:{path:e,value:t,key:"consumes_value"}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.changeParam"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>changeParam (e, t, r, n)](#apidoc.element.swagger-ui.plugins.SpecActions.changeParam)
- description and source-code
```javascript
function c(e, t, r, n){return{type:T,payload:{path:e,value:r,paramName:t,isXml:n}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.changeProducesValue"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>changeProducesValue (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.changeProducesValue)
- description and source-code
```javascript
function d(e, t){return{type:M,payload:{path:e,value:t,key:"produces_value"}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.clearRequest"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>clearRequest (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.clearRequest)
- description and source-code
```javascript
function h(e, t){return{type:R,payload:{path:e,method:t}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.clearResponse"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>clearResponse (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.clearResponse)
- description and source-code
```javascript
function y(e, t){return{type:A,payload:{path:e,method:t}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.clearValidateParams"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>clearValidateParams (e)](#apidoc.element.swagger-ui.plugins.SpecActions.clearValidateParams)
- description and source-code
```javascript
function p(e){return{type:q,payload:{pathMethod:e}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.execute"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>execute ()](#apidoc.element.swagger-ui.plugins.SpecActions.execute)
- description and source-code
```javascript
execute = function (){var e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:{},t=e.path,r=e.method,n=o(e,["path","method"]);return
function(e){var o=e.fn.fetch,a=e.specSelectors,u=e.specActions,i=a.spec().toJS(),s=a.operationScheme(t,r),c=a.contentTypeValues([
t,r]).toJS(),l=c.requestContentType,p=c.responseContentType,f=/xml/i.test(l),d=a.parameterValues([t,r],f).toJS();return u.executeRequest
(v({fetch:o,spec:i,pathName:t,method:r,parameters:d,requestContentType:l,scheme:s,responseContentType:p},n))}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.executeRequest"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>executeRequest (e)](#apidoc.element.swagger-ui.plugins.SpecActions.executeRequest)
- description and source-code
```javascript
executeRequest = function (e){return function(t){var r=t.fn,n=t.specActions,o=t.specSelectors,a=e.pathName,u=e.method,i=Object.assign({contextUrl
:o.url()},e);return a&&u&&(i.operationId=u.toLowerCase()+"-"+a),i=r.buildRequest(i),n.setRequest(e.pathName,e.method,i),r.execute
(e).then(function(t){return n.setResponse(e.pathName,e.method,t)}).catch(function(t){return n.setResponse(e.pathName,e.method,{error
:!0,err:(0,j.default)(t)})})}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.formatIntoYaml"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>formatIntoYaml ()](#apidoc.element.swagger-ui.plugins.SpecActions.formatIntoYaml)
- description and source-code
```javascript
formatIntoYaml = function (){return function(e){var t=e.specActions,r=e.specSelectors,n=r.specStr,o=t.updateSpec;try{var a=_.default.safeDump(_.default
.safeLoad(n()),{indent:2});o(a)}catch(e){o(e)}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.logRequest"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>logRequest (e)](#apidoc.element.swagger-ui.plugins.SpecActions.logRequest)
- description and source-code
```javascript
logRequest = function (e){return{payload:e,type:k}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.parseToJson"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>parseToJson (e)](#apidoc.element.swagger-ui.plugins.SpecActions.parseToJson)
- description and source-code
```javascript
parseToJson = function (e){
return function(t){var r=t.specActions,n=t.specSelectors,o=t.errActions,a=n.specStr,u=null;try{e=e||a(),o.clear({source:"parser"}),
u=_.default.safeLoad(e)}catch(e){return console.error(e),o.newSpecErr({source:"parser",level:"error",message:e.reason,line:e.mark
&&e.mark.line?e.mark.line+1:void 0})}return r.updateJsonSpec(u)}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.resolveSpec"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>resolveSpec (e, t)](#apidoc.element.swagger-ui.plugins.SpecActions.resolveSpec)
- description and source-code
```javascript
resolveSpec = function (e, t){return function(r){var n=r.specActions,o=r.specSelectors,a=r.errActions,u=r.fn,i=u.fetch,s=u.resolve,c=u.AST;"undefined
"==typeof e&&(e=o.specJson()),"undefined"==typeof t&&(t=o.url());var l=c.getLineNumberForPath,p=o.specStr();return s({fetch:i,spec
:e,baseDoc:t}).then(function(e){var t=e.spec,r=e.errors;if(a.clear({type:"thrown"}),r.length>0){var o=r.map(function(e){return console
.error(e),e.line=e.fullPath?l(p,e.fullPath):null,e.path=e.fullPath?e.fullPath.join("."):null,e.level="error",e.type="thrown",e.source
="resolver",Object.defineProperty(e,"message",{enumerable:!0,value:e.message}),e});a.newThrownErrBatch(o)}return n.updateResolved
(t)})}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.setRequest"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>setRequest (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecActions.setRequest)
- description and source-code
```javascript
setRequest = function (e, t, r){return{payload:{path:e,method:t,req:r},type:C}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.setResponse"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>setResponse (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecActions.setResponse)
- description and source-code
```javascript
setResponse = function (e, t, r){return{payload:{path:e,method:t,res:r},type:x}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.setScheme"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>setScheme (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecActions.setScheme)
- description and source-code
```javascript
function m(e, t, r){return{type:I,payload:{scheme:e,path:t,method:r}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.updateJsonSpec"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>updateJsonSpec (e)](#apidoc.element.swagger-ui.plugins.SpecActions.updateJsonSpec)
- description and source-code
```javascript
function s(e){if(!e||"object"!==("undefined"==typeof e?"undefined":b(e)))throw new Error("updateJson must only accept a simple JSON
 object");return{type:P,payload:e}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.updateResolved"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>updateResolved (e)](#apidoc.element.swagger-ui.plugins.SpecActions.updateResolved)
- description and source-code
```javascript
function u(e){return{type:N,payload:e}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.updateSpec"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>updateSpec (e)](#apidoc.element.swagger-ui.plugins.SpecActions.updateSpec)
- description and source-code
```javascript
function a(e){return e instanceof Error?{type:w,error:!0,payload:e}:"string"==typeof e?{type:w,payload:e.replace(/\t/g,"  ")||""}:{
type:w,payload:""}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.updateUrl"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>updateUrl (e)](#apidoc.element.swagger-ui.plugins.SpecActions.updateUrl)
- description and source-code
```javascript
function i(e){return{type:O,payload:e}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecActions.validateParams"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecActions.</span>validateParams (e)](#apidoc.element.swagger-ui.plugins.SpecActions.validateParams)
- description and source-code
```javascript
function l(e){return{type:S,payload:{pathMethod:e}}}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.SpecReducers"></a>[module swagger-ui.plugins.SpecReducers](#apidoc.module.swagger-ui.plugins.SpecReducers)

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.set_scheme"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>set_scheme (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.set_scheme)
- description and source-code
```javascript
set_scheme = function (e, t){var r=t.payload,n=r.scheme,o=r.path,a=r.method;return o&&a?e.setIn(["scheme",o,a],n):o||a?void 0:e.setIn(["scheme
","_defaultScheme"],n)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_clear_request"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_clear_request (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_clear_request)
- description and source-code
```javascript
spec_clear_request = function (e, t){var r=t.payload,n=r.path,o=r.method;return e.deleteIn(["requests",n,o])}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_clear_response"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_clear_response (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_clear_response)
- description and source-code
```javascript
spec_clear_response = function (e, t){var r=t.payload,n=r.path,o=r.method;return e.deleteIn(["responses",n,o])}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_clear_validate_param"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_clear_validate_param (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_clear_validate_param)
- description and source-code
```javascript
spec_clear_validate_param = function (e, t){var r=t.payload.pathMethod;return e.updateIn(["resolved","paths"].concat(a(r),["parameters"]),(0,i.fromJS)([]),function
(e){return e.withMutations(function(e){for(var t=0,r=e.count();t<r;t++)e.setIn([t,"errors"],(0,i.fromJS)({}))})})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_set_request"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_set_request (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_set_request)
- description and source-code
```javascript
spec_set_request = function (e, t){var r=t.payload,n=r.req,o=r.path,a=r.method;return e.setIn(["requests",o,a],(0,s.fromJSOrdered)(n))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_set_response"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_set_response (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_set_response)
- description and source-code
```javascript
spec_set_response = function (e, t){var r=t.payload,n=r.res,o=r.path,a=r.method,u=void 0;u=n.error?Object.assign({error:!0},n.err):n,u.headers=u.headers
||{};var i=e.setIn(["responses",o,a],(0,s.fromJSOrdered)(u));return n.data instanceof l.default.Blob&&(i=i.setIn(["responses",o,
a,"text"],n.data)),i}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_json"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_json (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_json)
- description and source-code
```javascript
spec_update_json = function (e, t){return e.set("json",(0,s.fromJSOrdered)(t.payload))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_operation_value"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_operation_value (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_operation_value)
- description and source-code
```javascript
spec_update_operation_value = function (e, t){var r=t.payload,n=r.path,o=r.value,u=r.key;return e.setIn(["resolved","paths"].concat(a(n),[u]),(0,i.fromJS)(o))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_param"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_param (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_param)
- description and source-code
```javascript
spec_update_param = function (e, t){var r=t.payload,n=r.path,o=r.paramName,u=r.value,c=r.isXml;return e.updateIn(["resolved","paths"].concat(a(n),["parameters
"]),(0,i.fromJS)([]),function(e){var t=e.findIndex(function(e){return e.get("name")===o});return u instanceof l.default.File||(u
=(0,s.fromJSOrdered)(u)),e.setIn([t,c?"value_xml":"value"],u)})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_resolved"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_resolved (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_resolved)
- description and source-code
```javascript
spec_update_resolved = function (e, t){return e.setIn(["resolved"],(0,s.fromJSOrdered)(t.payload))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_spec"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_spec (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_spec)
- description and source-code
```javascript
spec_update_spec = function (e, t){return"string"==typeof t.payload?e.set("spec",t.payload):e}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_url"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_update_url (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_update_url)
- description and source-code
```javascript
spec_update_url = function (e, t){return e.set("url",t.payload+"")}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecReducers.spec_validate_param"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecReducers.</span>spec_validate_param (e, t)](#apidoc.element.swagger-ui.plugins.SpecReducers.spec_validate_param)
- description and source-code
```javascript
spec_validate_param = function (e, t){var r=t.payload.pathMethod,n=e.getIn(["resolved","paths"].concat(a(r))),o=/xml/i.test(n.get("consumes_value"));return
 e.updateIn(["resolved","paths"].concat(a(r),["parameters"]),(0,i.fromJS)([]),function(e){return e.withMutations(function(e){for
(var t=0,r=e.count();t<r;t++){var n=(0,s.validateParam)(e.get(t),o);e.setIn([t,"errors"],(0,i.fromJS)(n))}})})}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.SpecSelectors"></a>[module swagger-ui.plugins.SpecSelectors](#apidoc.module.swagger-ui.plugins.SpecSelectors)

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.allowTryItOutFor"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>allowTryItOutFor ()](#apidoc.element.swagger-ui.plugins.SpecSelectors.allowTryItOutFor)
- description and source-code
```javascript
allowTryItOutFor = function (){return!0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.basePath"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>basePath (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.basePath)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.canExecuteScheme"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>canExecuteScheme (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.canExecuteScheme)
- description and source-code
```javascript
canExecuteScheme = function (e, t, r){return["http","https"].indexOf(A(e,t,r))>-1}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.consumes"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>consumes (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.consumes)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.contentTypeValues"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>contentTypeValues (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.contentTypeValues)
- description and source-code
```javascript
function s(e, t){var r=b(e).getIn(["paths"].concat(n(t)),(0,f.fromJS)({})),o=r.get("parameters")||new f.List,a=i(o,"file")?"multipart
/form-data":u(o,"formData")?"application/x-www-form-urlencoded":r.get("consumes_value");return(0,f.fromJS)({requestContentType:a
,responseContentType:r.get("produces_value")})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.definitions"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>definitions (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.definitions)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.externalDocs"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>externalDocs (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.externalDocs)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.findDefinition"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>findDefinition (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.findDefinition)
- description and source-code
```javascript
findDefinition = function (e, t){return v(e).getIn(["definitions",t],null)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.getParameter"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>getParameter (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.getParameter)
- description and source-code
```javascript
function o(e, t, r){var o=b(e).getIn(["paths"].concat(n(t),["parameters"]),(0,f.fromJS)([]));return o.filter(function(e){return f.
Map.isMap(e)&&e.get("name")===r}).first()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.hasHost"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>hasHost (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.hasHost)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.host"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>host (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.host)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.info"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>info (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.info)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.lastError"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>lastError (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.lastError)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.operationConsumes"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operationConsumes (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operationConsumes)
- description and source-code
```javascript
function c(e, t){return b(e).getIn(["paths"].concat(n(t),["consumes"]),(0,f.fromJS)({}))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.operationScheme"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operationScheme (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operationScheme)
- description and source-code
```javascript
operationScheme = function (e, t, r){return e.getIn(["scheme",t,r])||e.getIn(["scheme","_defaultScheme"])||"http"}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.operations"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operations (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operations)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.operationsWithRootInherited"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operationsWithRootInherited (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operationsWithRootInherited)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.operationsWithTags"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>operationsWithTags (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.operationsWithTags)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.parameterValues"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>parameterValues (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.parameterValues)
- description and source-code
```javascript
function a(e, t, r){var o=b(e).getIn(["paths"].concat(n(t),["parameters"]),(0,f.fromJS)([]));return o.reduce(function(e,t){var n=r
&&"body"===t.get("in")?t.get("value_xml"):t.get("value");return e.set(t.get("name"),n)},(0,f.fromJS)({}))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.parametersIncludeIn"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>parametersIncludeIn (e)](#apidoc.element.swagger-ui.plugins.SpecSelectors.parametersIncludeIn)
- description and source-code
```javascript
function u(e){var t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:"";if(f.List.isList(e))return e.some(function(e){return
 f.Map.isMap(e)&&e.get("in")===t})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.parametersIncludeType"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>parametersIncludeType (e)](#apidoc.element.swagger-ui.plugins.SpecSelectors.parametersIncludeType)
- description and source-code
```javascript
function i(e){var t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:"";if(f.List.isList(e))return e.some(function(e){return
 f.Map.isMap(e)&&e.get("type")===t})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.paths"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>paths (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.paths)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.produces"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>produces (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.produces)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.requestFor"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>requestFor (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.requestFor)
- description and source-code
```javascript
requestFor = function (e, t, r){return k(e).getIn([t,r],null)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.requests"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>requests (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.requests)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.responseFor"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>responseFor (e, t, r)](#apidoc.element.swagger-ui.plugins.SpecSelectors.responseFor)
- description and source-code
```javascript
responseFor = function (e, t, r){return C(e).getIn([t,r],null)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.responses"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>responses (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.responses)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.schemes"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>schemes (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.schemes)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.security"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>security (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.security)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.securityDefinitions"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>securityDefinitions (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.securityDefinitions)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.semver"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>semver (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.semver)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.spec"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>spec (e)](#apidoc.element.swagger-ui.plugins.SpecSelectors.spec)
- description and source-code
```javascript
spec = function (e){var t=v(e);return t.count()<1&&(t=m(e)),t}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.specJson"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>specJson (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.specJson)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.specResolved"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>specResolved (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.specResolved)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.specSource"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>specSource (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.specSource)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.specStr"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>specStr (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.specStr)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.tagDetails"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>tagDetails (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.tagDetails)
- description and source-code
```javascript
tagDetails = function (e, t){var r=T(e)||(0,f.List)();return r.filter(f.Map.isMap).find(function(e){return e.get("name")===t},(0,f.Map)())}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.taggedOperations"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>taggedOperations (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.taggedOperations)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.tags"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>tags (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.tags)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.url"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>url (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.url)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.validateBeforeExecute"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>validateBeforeExecute (e, t)](#apidoc.element.swagger-ui.plugins.SpecSelectors.validateBeforeExecute)
- description and source-code
```javascript
validateBeforeExecute = function (e, t){var r=b(e).getIn(["paths"].concat(n(t),["parameters"]),(0,f.fromJS)([])),o=!0;return r.forEach(function(e){var t=
e.get("errors");t&&t.count()&&(o=!1)}),o}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecSelectors.version"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecSelectors.</span>version (state, props)](#apidoc.element.swagger-ui.plugins.SpecSelectors.version)
- description and source-code
```javascript
function selector(state, props) {
  for (var _len4 = arguments.length, args = Array(_len4 > 2 ? _len4 - 2 : 0), _key4 = 2; _key4 < _len4; _key4++) {
    args[_key4 - 2] = arguments[_key4];
  }

  var params = dependencies.map(function (dependency) {
    return dependency.apply(undefined, [state, props].concat(args));
  });
  return memoizedResultFunc.apply(undefined, _toConsumableArray(params));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.SpecWrapActions"></a>[module swagger-ui.plugins.SpecWrapActions](#apidoc.module.swagger-ui.plugins.SpecWrapActions)

#### <a name="apidoc.element.swagger-ui.plugins.SpecWrapActions.executeRequest"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecWrapActions.</span>executeRequest (e, t)](#apidoc.element.swagger-ui.plugins.SpecWrapActions.executeRequest)
- description and source-code
```javascript
executeRequest = function (e, t){var r=t.specActions;return function(t){return r.logRequest(t),e(t)}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecWrapActions.updateJsonSpec"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecWrapActions.</span>updateJsonSpec (e, t)](#apidoc.element.swagger-ui.plugins.SpecWrapActions.updateJsonSpec)
- description and source-code
```javascript
updateJsonSpec = function (e, t){var r=t.specActions;return function(){e.apply(void 0,arguments),r.resolveSpec.apply(r,arguments)}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.SpecWrapActions.updateSpec"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SpecWrapActions.</span>updateSpec (e, t)](#apidoc.element.swagger-ui.plugins.SpecWrapActions.updateSpec)
- description and source-code
```javascript
updateSpec = function (e, t){var r=t.specActions;return function(){e.apply(void 0,arguments),r.parseToJson.apply(r,arguments)}}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.SplitPaneModeComponentsIndex"></a>[module swagger-ui.plugins.SplitPaneModeComponentsIndex](#apidoc.module.swagger-ui.plugins.SplitPaneModeComponentsIndex)

#### <a name="apidoc.element.swagger-ui.plugins.SplitPaneModeComponentsIndex.SplitPaneMode"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.SplitPaneModeComponentsIndex.</span>SplitPaneMode ()](#apidoc.element.swagger-ui.plugins.SplitPaneModeComponentsIndex.SplitPaneMode)
- description and source-code
```javascript
function t(){var e,r,n,u;o(this,t);for(var i=arguments.length,s=Array(i),c=0;c<i;c++)s[c]=arguments[c];return r=n=a(this,(e=t.__proto__
||Object.getPrototypeOf(t)).call.apply(e,[this].concat(s))),n.onDragFinished=function(){var e=n.props,t=e.threshold,r=e.layoutActions
,o=n.refs.splitPane.state,a=o.position,u=o.draggedSize;n.draggedSize=u;var i=a<=t,s=u<=t;r.changeMode(f,i?y:s?d:h)},n.sizeFromMode
=function(e,t){return e===d?(n.draggedSize=null,"0px"):e===y?(n.draggedSize=null,"100%"):n.draggedSize||t},u=r,a(n,u)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.plugins.ViewRootInjects"></a>[module swagger-ui.plugins.ViewRootInjects](#apidoc.module.swagger-ui.plugins.ViewRootInjects)

#### <a name="apidoc.element.swagger-ui.plugins.ViewRootInjects.getComponent"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ViewRootInjects.</span>getComponent (e, t, r, n, o)](#apidoc.element.swagger-ui.plugins.ViewRootInjects.getComponent)
- description and source-code
```javascript
getComponent = function (e, t, r, n, o){if("string"!=typeof n)throw new TypeError("Need a string, to fetch a component. Was given a "+("undefined"==
typeof n?"undefined":i(n)));var a=r(n);return a?o?"root"===o?g(e,a,t()):g(e,a):w(a):(e().log.warn("Could not find component",n),
null)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ViewRootInjects.makeMappedContainer"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ViewRootInjects.</span>makeMappedContainer (e, t, r, n, i, s)](#apidoc.element.swagger-ui.plugins.ViewRootInjects.makeMappedContainer)
- description and source-code
```javascript
makeMappedContainer = function (e, t, r, n, i, s){return function(t){function n(t,r){o(this,n);var u=a(this,(n.__proto__||Object.getPrototypeOf(n)).call(this
,t,r));return _(e,s,t,{}),u}return u(n,t),c(n,[{key:"componentWillReceiveProps",value:function(t){_(e,s,t,this.props)}},{key:"render
",value:function(){var e=(0,m.default)(this.props,s?Object.keys(s):[]),t=r(i,"root");return p.default.createElement(t,e)}}]),n}(
l.Component)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.swagger-ui.plugins.ViewRootInjects.render"></a>[function <span class="apidocSignatureSpan">swagger-ui.plugins.ViewRootInjects.</span>render (e, t, r, n, o)](#apidoc.element.swagger-ui.plugins.ViewRootInjects.render)
- description and source-code
```javascript
render = function (e, t, r, n, o){var a=document.querySelector(o),u=r(e,t,n,"App","root");d.default.render(p.default.createElement(u,null),a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.swagger-ui.presets"></a>[module swagger-ui.presets](#apidoc.module.swagger-ui.presets)

#### <a name="apidoc.element.swagger-ui.presets.apis"></a>[function <span class="apidocSignatureSpan">swagger-ui.presets.</span>apis ()](#apidoc.element.swagger-ui.presets.apis)
- description and source-code
```javascript
function o(){return[u.default]}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
