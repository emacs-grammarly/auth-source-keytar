[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![MELPA](https://melpa.org/packages/auth-source-keytar-badge.svg)](https://melpa.org/#/auth-source-keytar)
[![MELPA Stable](https://stable.melpa.org/packages/auth-source-keytar-badge.svg)](https://stable.melpa.org/#/auth-source-keytar)

# auth-source-keytar

[![CI](https://github.com/emacs-grammarly/auth-source-keytar/actions/workflows/test.yml/badge.svg)](https://github.com/emacs-grammarly/auth-source-keytar/actions/workflows/test.yml)

Emacs Lisp interface for [node-keytar](https://www.npmjs.com/package/keytar)
using [@emacs-grammarly/keytar-cli](https://github.com/emacs-grammarly/keytar-cli).

## Installation

You will need [@emacs-grammarly/keytar-cli](https://github.com/emacs-grammarly/keytar-cli)
before using this library.

```bash
npm install -g @emacs-grammarly/keytar-cli
```

or after you have installed `auth-source-keytar.el` in your `load-path`. Do the following,

```el
(require 'auth-source-keytar)
(keytar-install)
```

## Usage

```el
(auth-source-keytar-enable)
(auth-source-keytar-search :service "service1" :account "testuser")
```

## Contribution

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
