# KLD
*Keditw32 Language Definition files*

Following a [github hello world](https://guides.github.com/activities/hello-world/#branch) guide with a [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) cheatsheet: KEDIT is a text editor based on IBM's [XEDIT](https://en.wikipedia.org/wiki/XEDIT) using a subset of [Rexx](https://en.wikipedia.org/wiki/Rexx) known as KEXX as its macro language; roughly the same idea as [EMACS](https://en.wikipedia.org/wiki/Emacs) and [LISP](https://en.wikipedia.org/wiki/Lisp_(programming_language)).

Keditw32 is a version for Windows offering *syntax highlighting*; roughly the same idea as *pygments* for [python](https://en.wikipedia.org/wiki/Python_(programming_language)). This repo contains my DIY language definition files:

1. **[batch](https://github.com/frank-e/KLD/blob/master/batch.kld "batch.kld")** for Windows cmd.exe scripts, file extension **.cmd**
2. **[config](https://github.com/frank-e/KLD/blob/master/config.kld "config.kld")** for PC DOS **config.sys** files (historic)
3. **[freeciv](https://github.com/frank-e/KLD/blob/master/freeciv.kld "freeciv.kld")** for Freeciv **.ruleset** and similar files
4. **[kld](https://github.com/frank-e/KLD/blob/master/kld.kld "kld.kld")** extends the built-in **kld.kld** syntax highlighting
5. **[lua](https://github.com/frank-e/KLD/blob/master/lua.kld "lua.kld")** (not only) for Freeciv **.lua** scripts
6. **[wasm](https://github.com/frank-e/KLD/blob/master/wasm.kld "wasm.kld")** for *Open Watcom* **.asm** files (experimental)

CAVEAT: These language definition files may help in viewing or editing sources for the relevant languages with KEDIT, but are unsuited for syntax checks. Notably **lua.kld** covers only a subset of the LUA syntax, *some* levels of long comments or multi-line strings, not *all* (255) levels, this is a limitation of KEDIT's syntax highlighting.

## Version 0.1 ##
*Download [v0.1.zip](https://github.com/frank-e/KLD/archive/v0.1.zip "2019") or [tarball](https://github.com/frank-e/KLD/archive/v0.1.tar.gz "2019")*
