# Avy Menu

[![License GPL 3](https://img.shields.io/badge/license-GPL_3-green.svg)](http://www.gnu.org/licenses/gpl-3.0.txt)
[![MELPA](https://melpa.org/packages/avy-menu-badge.svg)](https://melpa.org/#/avy-menu)
[![Build Status](https://travis-ci.org/mrkkrp/avy-menu.svg?branch=master)](https://travis-ci.org/mrkkrp/avy-menu)

The library provides [`avy`](https://github.com/abo-abo/avy)-powered popup
menu that allows to quickly choose from available options. This is used in
the following packages:

* [`ace-popup-menu`](https://github.com/mrkkrp/ace-popup-menu)
* [`char-menu`](https://github.com/mrkkrp/char-menu)
* [`hasky-extensions`](https://github.com/hasky-mode/hasky-extensions)

You can use it directly for your custom needs as well.

## Installation

Put it on your `load-path` and then add the following at the top of file
where you would like to use the menu:

```emacs-lisp
(require 'avy-menu)
```

That's it. Don't forget to include it in your list of dependencies if you
are writing an Emacs Lisp package:

```emacs-lisp
;; Package-Requires: ((emacs "24.5") (avy-menu "0.1"))
```

To install the package via MELPA, type <kbd>M-x package-install avy-menu
RET</kbd>.

## API

The single public function `avy-menu` provides all the functionality. See
its description in source code or with built-in help system: <kbd>C-h f
avy-menu RET</kbd>.

## Customization

Use <kbd>M-x customize-group avy-menu RET</kbd> to change appearance of the
menu.

## License

Copyright © 2016–2017 Mark Karpov

Distributed under GNU GPL, version 3.
