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

## Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple)](https://github.com/bbatsov/emacs-lisp-style-guide)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)
[![Become a patron](https://img.shields.io/badge/patreon-become%20a%20patron-orange.svg?logo=patreon)](https://www.patreon.com/jcs090218)

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
