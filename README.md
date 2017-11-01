# xterm.js and webpack testbed

This is a testbed repo to get xterm.js working with webpack.

## Current status

Right now running `npm run build` produces the following error

```
Hash: ad015a893c459fa739cb
Version: webpack 3.8.1
Time: 3712ms
    Asset     Size  Chunks             Chunk Names
bundle.js  3.08 kB       0  [emitted]  main
   [0] ./src/index.ts 288 bytes {0} [built]
    + 1 hidden module

ERROR in ./node_modules/xterm/src/Terminal.ts
Module parse failed: Unexpected token (51:8)
You may need an appropriate loader to handle this file type.
|
| // Declares required for loadAddon
| declare var exports: any;
| declare var module: any;
| declare var define: any;
 @ ./src/index.ts 3:17-46

npm ERR! Linux 4.4.0-98-generic
npm ERR! argv "/usr/local/bin/node" "/usr/local/bin/npm" "run" "build"
npm ERR! node v7.2.1
npm ERR! npm  v3.10.10
```
