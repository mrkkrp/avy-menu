# Avy Menu

[![License GPL 3](https://img.shields.io/badge/license-GPL_3-green.svg)](http://www.gnu.org/licenses/gpl-3.0.txt)
[![MELPA](https://melpa.org/packages/avy-menu-badge.svg)](https://melpa.org/#/avy-menu)
[![CI](https://github.com/mrkkrp/avy-menu/actions/workflows/ci.yaml/badge.svg)](https://github.com/mrkkrp/avy-menu/actions/workflows/ci.yaml)

The library provides an [`avy`](https://github.com/abo-abo/avy)-powered
popup menu. It is used in (at least) the following packages:

* [`ace-popup-menu`](https://github.com/mrkkrp/ace-popup-menu)
* [`char-menu`](https://github.com/mrkkrp/char-menu)
* [`hasky-extensions`](https://github.com/hasky-mode/hasky-extensions)

It can also be used directly.

## Installation

The package is available via MELPA, so you can just type `M-x
package-install RET avy-menu RET`.

If you would like to install the package manually, download or clone it and
put on Emacs' `load-path`. Then you can require it in your init file like
this:

```emacs-lisp
(require 'avy-menu)
```

Don't forget to include it in your list of dependencies if you are writing
an Emacs Lisp package:

```emacs-lisp
;; Package-Requires: ((emacs "24.5") (avy-menu "0.1"))
```

## API

See the description of `avy-menu` in the source code or by typing `C-h f
avy-menu RET`.

## Customization

Use `M-x customize-group avy-menu RET` to change appearance of the menu.

## License

Copyright © 2016–present Mark Karpov

Distributed under GNU GPL, version 3.
