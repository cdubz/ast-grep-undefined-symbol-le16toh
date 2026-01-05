# @ast-grep/napi@0.40.x

1. `npm install`
2. `npm why @ast-grep/napi`: @ast-grep/napi@0.40.4
3. `node -e 'console.log(require("@ast-grep/napi").Lang.JavaScript)'`

```shell
/workspaces/ast-grep/node_modules/@ast-grep/napi/index.js:385
    throw new Error(
    ^

Error: Cannot find native binding. npm has a bug related to optional dependencies (https://github.com/npm/cli/issues/4828). Please try `npm i` again after removing both package-lock.json and node_modules directory.
    at Object.<anonymous> (/workspaces/ast-grep/node_modules/@ast-grep/napi/index.js:385:11)
    at Module._compile (node:internal/modules/cjs/loader:1761:14)
    at Object..js (node:internal/modules/cjs/loader:1893:10)
    at Module.load (node:internal/modules/cjs/loader:1481:32)
    at Module._load (node:internal/modules/cjs/loader:1300:12)
    at TracingChannel.traceSync (node:diagnostics_channel:328:14)
    at wrapModuleLoad (node:internal/modules/cjs/loader:245:24)
    at Module.require (node:internal/modules/cjs/loader:1504:12)
    at require (node:internal/modules/helpers:152:16)
    at [eval]:1:13 {
  [cause]: [
    Error: Cannot find module './ast-grep-napi.linux-arm64-gnu.node'
    Require stack:
    - /workspaces/ast-grep/node_modules/@ast-grep/napi/index.js
        at Module._resolveFilename (node:internal/modules/cjs/loader:1421:15)
        at defaultResolveImpl (node:internal/modules/cjs/loader:1059:19)
        at resolveForCJSWithHooks (node:internal/modules/cjs/loader:1064:22)
        at Module._load (node:internal/modules/cjs/loader:1227:37)
        at TracingChannel.traceSync (node:diagnostics_channel:328:14)
        at wrapModuleLoad (node:internal/modules/cjs/loader:245:24)
        at Module.require (node:internal/modules/cjs/loader:1504:12)
        at require (node:internal/modules/helpers:152:16)
        at requireNative (/workspaces/ast-grep/node_modules/@ast-grep/napi/index.js:237:18)
        at Object.<anonymous> (/workspaces/ast-grep/node_modules/@ast-grep/napi/index.js:362:17) {
      code: 'MODULE_NOT_FOUND',
      requireStack: [ '/workspaces/ast-grep/node_modules/@ast-grep/napi/index.js' ]
    },
    Error: /workspaces/ast-grep/node_modules/@ast-grep/napi-linux-arm64-gnu/ast-grep-napi.linux-arm64-gnu.node: undefined symbol: le16toh
        at Object..node (node:internal/modules/cjs/loader:1920:18)
        at Module.load (node:internal/modules/cjs/loader:1481:32)
        at Module._load (node:internal/modules/cjs/loader:1300:12)
        at TracingChannel.traceSync (node:diagnostics_channel:328:14)
        at wrapModuleLoad (node:internal/modules/cjs/loader:245:24)
        at Module.require (node:internal/modules/cjs/loader:1504:12)
        at require (node:internal/modules/helpers:152:16)
        at requireNative (/workspaces/ast-grep/node_modules/@ast-grep/napi/index.js:242:18)
        at Object.<anonymous> (/workspaces/ast-grep/node_modules/@ast-grep/napi/index.js:362:17)
        at Module._compile (node:internal/modules/cjs/loader:1761:14) {
      code: 'ERR_DLOPEN_FAILED'
    }
  ]
}

Node.js v24.12.0
```

# @ast-grep/napi@0.39.9

1. `npm install @ast-grep/napi@0.39.9`
2. `npm why @ast-grep/napi`: @ast-grep/napi@0.39.9
3. `node -e 'console.log(require("@ast-grep/napi").Lang.JavaScript)'`

```shell
JavaScript
```
