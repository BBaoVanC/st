# bbaovanc's st fork

## Table of Contents

- [bbaovanc's st fork](#bbaovancs-st-fork)
  - [Table of Contents](#table-of-contents)
  - [Dependencies](#dependencies)
  - [Changes](#changes)
    - [Patches](#patches)
    - [Features and Tweaks](#features-and-tweaks)
  - [Installation](#installation)

## Dependencies

- [st-edit-screen](https://git.bbaovanc.com/bbaovanc/dotfiles/src/branch/master/.local/bin/st-edit-screen) script from my dotfiles
- A system-wide `monospace` font configured (preferably with nerd-font)

## Changes

### Patches

- [alpha](https://st.suckless.org/patches/alpha)
- [scrollback](https://st.suckless.org/patches/scrollback)
- [scrollback-mouse](https://st.suckless.org/patches/scrollback)
- [newterm](https://st.suckless.org/patches/newterm)
- [ligatures](https://st.suckless.org/patches/ligatures)
- [externalpipe](https://st.suckless.org/patches/externalpipe)
- [externalpipe-eternal](https://st.suckless.org/patches/externalpipe)

### Features and Tweaks

- [Nord theme](https://nordtheme.com)
- Use system monospace font
- `Shift+Insert` pastes from clipboard, not selection board
- `Ctrl+Shift+E`: send total contents of scrollback to $EDITOR

## Installation

1. Run `make`
2. Run `sudo make install`

By default, `st` will be installed to `/usr/local/bin` and manpages to `/usr/local/share/man/man1`