
----JXcore 3.1.1

- npm updated to 3.3.12
- native packages: ignore jxp.library GH #784
- manifest file: releases.json GH #686
- jx packaging: preserve chmod GH #770
- jx packaging: fixed fs.exists/stat/etc. against __filename GH #783
- fixed GH #780
- fix EventEmitter with fake ReadStream GH #775
- android build: compress internals by default for embedded
- android: fixes SIGSEGV after calling CWD
- skip reading jx.config when process._eval is set GH #756
- jxcore.utils: add linaro to getOS list
- chakra: Enable Async/Await GH #741
- chakra: fix console.trace
- chakra: fixed mt errors GH #737
- remove executable bit from non-executable files (@jsonkarns)
- jx-ni: JX_CallFunction support for function param GH #745
