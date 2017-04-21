# npmtest-react-burger-menu

#### basic test coverage for  [react-burger-menu (v2.0.0)](https://github.com/negomi/react-burger-menu)  [![npm package](https://img.shields.io/npm/v/npmtest-react-burger-menu.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-burger-menu) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-burger-menu.svg)](https://travis-ci.org/npmtest/node-npmtest-react-burger-menu)

#### An off-canvas sidebar component with a collection of effects and styles using CSS transitions and SVG path animations

[![NPM](https://nodei.co/npm/react-burger-menu.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-burger-menu)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-burger-menu/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-burger-menu/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-burger-menu/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-burger-menu/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-burger-menu/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-burger-menu/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-burger-menu/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-burger-menu/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-burger-menu/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-burger-menu/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-burger-menu/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-burger-menu/build/test-report.html](https://npmtest.github.io/node-npmtest-react-burger-menu/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-burger-menu/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-burger-menu/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-burger-menu/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-burger-menu/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-burger-menu/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-burger-menu/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-burger-menu/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-burger-menu/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-burger-menu",
    "version": "2.0.0",
    "description": "An off-canvas sidebar component with a collection of effects and styles using CSS transitions and SVG path animations",
    "main": "lib/BurgerMenu.js",
    "author": "Imogen Wentworth",
    "homepage": "https://github.com/negomi/react-burger-menu",
    "repository": {
        "type": "git",
        "url": "https://github.com/negomi/react-burger-menu.git"
    },
    "bugs": {
        "url": "https://github.com/negomi/react-burger-menu/issues"
    },
    "dependencies": {
        "browserify-optional": "^1.0.0",
        "classnames": "^2.1.1",
        "eve": "~0.4.2",
        "prop-types": "^15.5.8",
        "snapsvg-cjs": "0.0.4"
    },
    "devDependencies": {
        "babel-core": "^6.3.26",
        "babel-eslint": "^7.0.0",
        "babel-preset-env": "^1.4.0",
        "babel-preset-react": "^6.3.13",
        "babel-register": "^6.3.13",
        "chai": "^3.2.0",
        "eslint": "^3.0.0",
        "eslint-plugin-react": "^6.0.0",
        "gulp": "^3.8.11",
        "gulp-git": "^2.0.0",
        "gulp-mocha": "^3.0.0",
        "jsdom": "^9.0.0",
        "mocha": "^3.0.0",
        "react": "^15.4.1",
        "react-component-gulp-tasks": "^0.7.1",
        "react-dom": "^15.4.1",
        "react-test-renderer": "^15.5.4",
        "sinon": "^2.1.0"
    },
    "peerDependencies": {
        "react": ">=0.14.0 <16.0.0",
        "react-dom": ">=0.14.0 <16.0.0"
    },
    "browserify": {
        "transform": [
            "browserify-optional"
        ]
    },
    "browserify-shim": {
        "react": "global:React",
        "react-dom": "global:ReactDOM",
        "snapsvg": "global:Snap"
    },
    "scripts": {
        "build": "gulp clean && NODE_ENV=production gulp build",
        "examples": "gulp dev:server",
        "lint": "eslint ./; true",
        "publish:site": "gulp publish:examples",
        "publish:version": "gulp commit:version && gulp push",
        "start": "gulp dev",
        "test": "gulp test --reporter list",
        "tdd": "gulp watch:tests --reporter min",
        "watch": "gulp watch:lib",
        "release": "npm run build && gulp bump && gulp release && npm run publish:version",
        "release:minor": "npm run build && gulp bump:minor && gulp release",
        "release:major": "npm run build && gulp bump:major && gulp release"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "readmeFilename": "README.md",
    "keywords": [
        "component",
        "hamburger",
        "menu",
        "react",
        "react-component"
    ],
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
