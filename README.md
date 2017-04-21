# npmtest-react-render-service

#### basic test coverage for  [react-render-service (v1.0.0)](https://github.com/mic159/react-render)  [![npm package](https://img.shields.io/npm/v/npmtest-react-render-service.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-render-service) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-render-service.svg)](https://travis-ci.org/npmtest/node-npmtest-react-render-service)

#### HTTP microservice for rendering React to HTML on the server side

[![NPM](https://nodei.co/npm/react-render-service.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-render-service)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-render-service/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-render-service/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-render-service/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-render-service/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-render-service/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-render-service/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-render-service/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-render-service/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-render-service/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-render-service/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-render-service/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-render-service/build/test-report.html](https://npmtest.github.io/node-npmtest-react-render-service/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-render-service/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-render-service/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-render-service/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-render-service/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-render-service/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-render-service/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-render-service/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-render-service/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-render-service",
    "version": "1.0.0",
    "description": "HTTP microservice for rendering React to HTML on the server side",
    "main": "render.js",
    "bin": {
        "react-service": "render.js"
    },
    "dependencies": {
        "body-parser": "^1.15.2",
        "express": "^4.14.0",
        "morgan": "^1.7.0",
        "react-dom": "^15.2",
        "react": "^15.2",
        "yargs": "^3.29.0"
    },
    "peerDependencies": {
        "react": "^0.14 || ^15.0",
        "react-dom": "^0.14 || ^15.0"
    },
    "author": "Michael Cooper",
    "repository": {
        "type": "git",
        "url": "https://github.com/mic159/react-render.git"
    },
    "keywords": [
        "react",
        "reactjs",
        "isomorphic",
        "templates"
    ],
    "homepage": "https://github.com/mic159/react-render",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
