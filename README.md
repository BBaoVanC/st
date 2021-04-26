# bbaovanc's st fork

## Table of Contents

- [bbaovanc's st fork](#bbaovancs-st-fork)
  - [Table of Contents](#table-of-contents)
  - [Dependencies](#dependencies)
  - [Changes](#changes)
    - [Patches](#patches)
    - [Features and Tweaks](#features-and-tweaks)
  - [Installation](#installation)
    - [Using `make`](#using-make)
    - [Using AUR](#using-aur)

## Dependencies

- **[libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra-git): Important!** - `st` will crash if you try and view emoji without this installed.
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

### Using `make`

1. Run `make`
2. Run `sudo make install`

By default, `st` will be installed to `/usr/local/bin` and manpages to `/usr/local/share/man/man1`

### Using AUR

1. Install the AUR package [st-bbaovanc-git](https://aur.archlinux.org/packages/st-bbaovanc-git)

By default, `st` will be installed to `/usr/bin` and manpages to `/usr/share/man/man1/`
