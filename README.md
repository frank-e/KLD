# KLD
Keditw32 Language Definition files

Following a [github hello world](https://guides.github.com/activities/hello-world/#branch) guide with a [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) cheatsheet: KEDIT is a text editor based on IBM's [XEDIT](https://en.wikipedia.org/wiki/XEDIT) using a subset of [Rexx](https://en.wikipedia.org/wiki/Rexx) known as KEXX as its macro language; roughly the same idea as [EMACS](https://en.wikipedia.org/wiki/Emacs) and [LISP](https://en.wikipedia.org/wiki/Lisp_(programming_language).

Keditw32 is a version for Windows offering *syntax highlighting*; roughly the same idea as *pygments* for [python](https://en.wikipedia.org/wiki/Python_(programming_language). This repo contains my DIY language definition files:

1. **batch** for Windows cmd.exe scripts, file extension **.cmd** 
2. **config** for PC DOS **config.sys** files (historic)
2. **freeciv** for Freeciv **.ruleset** and similar files
2. **KLD** extends the built-in **kld.kld** syntax highlighting
2. **lua** (not only) for Freeciv **.lua** scripts
2. **wasm** for *Open Watcom* **.asm** files (experimental)

CAVEAT: These language definition files may help in viewing or editing sources for the relevant languages with KEDIT, but are unsuited for syntax checks. Notably **lua.kld** covers only a subset of the LUA syntax, *some* levels of long comments or multi-line strings, not *all* (255) levels, this is a limitation of KEDIT's syntax highlighting.
