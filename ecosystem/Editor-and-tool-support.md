
## Editors

#### Atom 

- [purescript-contrib/atom-language-purescript](https://github.com/purescript-contrib/atom-language-purescript) provides syntax highlighting
- [nwolverson/atom-ide-purescript](https://github.com/nwolverson/atom-ide-purescript) provides build support,   REPL, and autocomplete etc. via [purs ide](https://github.com/purescript/purescript/tree/master/psc-ide)

#### Emacs
 Either use these two:
- [dysinger/purescript-mode](https://github.com/dysinger/purescript-mode) was adapted from haskell-mode
- [epost/psc-ide-emacs](https://github.com/epost/psc-ide-emacs) offers Emacs support for [psc-ide](https://github.com/purescript/purescript/tree/master/psc-ide)

Or these two, for a more minimal setup:

- [emacs-pe/purescript-mode](https://github.com/emacs-pe/purescript-mode) is an alpha-stage greenfield mode
- [emacs-pe/flycheck-purescript](https://github.com/emacs-pe/flycheck-purescript) provides flycheck support.

PSCI support via comint:

- [ardumont/psci-mode](https://github.com/ardumont/emacs-psci) is a REPL minor mode

Spacemacs users can just use the [`purescript` layer](https://github.com/syl20bnr/spacemacs/tree/master/layers/%2Blang/purescript).

#### Sublime Text 2

- [PureScript package](https://sublime.wbond.net/search/PureScript) by joneshf

#### Vim

- [purescript-vim](https://github.com/raichoo/purescript-vim) syntax highlighting and indentation
- [FrigoEU/psc-ide-vim](https://github.com/FrigoEU/psc-ide-vim/)

#### VS Code

- [nwolverson/vscode-ide-purescript](https://github.com/nwolverson/vscode-ide-purescript)

#### General

- To generate `TAGS` files, use `purs docs --format etags` (or `--format ctags`)

## Build tools and package managers

- [Pulp](https://github.com/bodil/pulp) - a standalone build system for PureScript ([pulp](https://www.npmjs.com/package/pulp) in `npm`)
- [psc-package](https://github.com/purescript/psc-package):  An experimental package manager for PureScript based on the concept of package sets
- [Purify](https://github.com/chrisdone/purify): Reproducible builds for PureScript
- [Gulp task](https://github.com/purescript-contrib/gulp-purescript) (`gulp-purescript` in `npm`)
- [psvm-js](https://github.com/ThomasCrvsr/psvm-js) - PureScript Version Manager
- [purs-loader](https://github.com/ethul/purs-loader/) - PureScript loader for WebPack
- [psc-pane](https://github.com/anttih/psc-pane) - Auto reloading compiler which formats a single error to fit the window
- [purescript-psa](https://github.com/natefaubion/purescript-psa) - A pretty, flexible error/warning reporting frontend for `psc` featuring colours, original source spans in errors, warning filtering and persistence.
- [pscid](https://github.com/kRITZCREEK/pscid) is a lightweight file-watcher/testrunner for PS projects, that uses `psc-ide` to provide fast rebuilds.
