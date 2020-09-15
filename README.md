# Kyoz's fork of the dynamic menu (dmenu) for X
> [dmenu](https://tools.suckless.org/dmenu/) is a simple, light weight, powerful dynamic menu for X, originally designed for [dwm](https://dwm.suckless.org/)

## Information
Base on [dmenu-5.0](https://dl.suckless.org/tools/dmenu-5.0.tar.gz) version.

Patchs:
  - [border-4.9](https://tools.suckless.org/dmenu/patches/border/)

## Requirements

In order to build dmenu you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (dmenu is installed into the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu (if necessary as root):

```
make clean install
```

# Running dmenu

See the man page for details.
