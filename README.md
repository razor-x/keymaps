# Keymaps

[![The Unlicense](https://img.shields.io/github/license/rxrc/keymaps.svg)](./LICENSE.txt)

## Description

These are my Xorg keymaps for the X KeyBoard extension (XKB).

For a usage example, see my [dotfiles].

[dotfiles]: https://github.com/rxrc/dotfiles

## Installation and Usage

Generate the default keymap for your system with

```bash
$ setxkbmap -print > xkb/keymap/default.xkb
```

Install `xkb` to `~/.config/xkb`.

Load a keymap with

```bash
$ xkbcomp -I$HOME/.config/xkb $HOME/.config/xkb/keymap/default.xkb $DISPLAY
```

## License

This is free and unencumbered software released into the public domain.

## Warranty

This software is provided "as is" and without any express or
implied warranties, including, without limitation, the implied
warranties of merchantibility and fitness for a particular
purpose.
