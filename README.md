# npmdoc-strongloop

#### api documentation for  [strongloop (v6.0.3)](http://www.strongloop.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-strongloop.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-strongloop) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-strongloop.svg)](https://travis-ci.org/npmdoc/node-npmdoc-strongloop)

#### StrongLoop Command Line Tools

[![NPM](https://nodei.co/npm/strongloop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/strongloop)

- [https://npmdoc.github.io/node-npmdoc-strongloop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-strongloop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-strongloop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-strongloop/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-strongloop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-strongloop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "strongloop",
    "version": "6.0.3",
    "description": "StrongLoop Command Line Tools",
    "homepage": "http://www.strongloop.com",
    "keywords": [
        "Backend",
        "LoopBack",
        "Mobile",
        "Platform",
        "StrongLoop",
        "alerts",
        "analytics",
        "agent",
        "apm",
        "build",
        "bundle",
        "cluster",
        "config",
        "dependencies",
        "deploy",
        "devops",
        "event loop",
        "forever",
        "git",
        "heap",
        "heroku",
        "logging",
        "mBaaS",
        "manager",
        "master",
        "memory",
        "metrics",
        "monitoring",
        "nodeops",
        "npm",
        "npmrc",
        "openshift",
        "ops",
        "performance",
        "pm",
        "process",
        "profiler",
        "profiling",
        "registry",
        "response",
        "runner",
        "service",
        "slc",
        "slowest functions",
        "streams",
        "strong-agent",
        "strong-cli",
        "strong-cluster-control",
        "strong-pm",
        "strong-supervisor",
        "strongloop",
        "strongops",
        "supervisor",
        "switch",
        "time",
        "upstart"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/strongloop/strongloop.git"
    },
    "author": "engineering@strongloop.com",
    "license": "Artistic-2.0",
    "readmeFilename": "README.md",
    "bin": {
        "slc": "./bin/slc.js",
        "lb-ng": "./node_modules/loopback-sdk-angular-cli/bin/lb-ng.js"
    },
    "scripts": {
        "pretest": "eslint --ignore-path .gitignore . && jscs .",
        "test": "tap --bail test/test-*.*"
    },
    "dependencies": {
        "async": "^0.9.0",
        "debug": "^2.1.0",
        "generator-loopback": "1.x",
        "loopback-sdk-angular-cli": "^2.1.0",
        "node-inspector": "~0.7.0",
        "nodefly-register": "~0.3.2",
        "nopt": "~3.0.1",
        "optimist": "^0.6.1",
        "read": "~1.0.5",
        "strong-agent": "^2.0.0",
        "strong-arc": "^1.2.0",
        "strong-build": "^2.0.0",
        "strong-deploy": "^3.x",
        "strong-mesh-models": "^8.0.0",
        "strong-pm": "^5.0.0",
        "strong-registry": "^1.0.0",
        "strong-start": "^1.1.0",
        "strong-supervisor": "^3.0.0",
        "which": "^1.1.1"
    },
    "devDependencies": {
        "eslint": "^1.1.0",
        "jscs": "^1.11.3",
        "tap": "^1.3.1"
    },
    "optionalDependencies": {
        "JSONStream": "^1.0.3",
        "bufferutil": "^1.2.1",
        "core-util-is": "^1.0.1",
        "d3": "^3.5.6",
        "heapdump": "^0.3.7",
        "inherits": "^2.0.1",
        "less": "~1.4.0",
        "lodash": "^3.10.1",
        "loopback": "^2.17.0",
        "loopback-datasource-juggler": "^2.41.0",
        "mime-db": "^1.19.0",
        "modern-syslog": "^1.1.2",
        "moment": "^2.10.0",
        "readable-stream": "^2.0.3",
        "spawn-sync": "^1.0.13",
        "sqlite3": "3.1.4",
        "strong-debugger": "^1.0.0",
        "strong-remoting": "^2.0.0",
        "strong-swagger-ui": "^21.0.1",
        "swagger-ui": "^2.1.3",
        "utf-8-validate": "^1.2.1",
        "wrappy": "1.0.1",
        "ws": "^0.8.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
