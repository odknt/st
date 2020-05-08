# st - simple terminal

The [suckless terminal](https://st.suckless.org) (st) with some additional features.

## Unique features

* color emoji support (ligature not support)
* XIM over-the-spot support

## Other st patches

* scrollback
* vertcenter
* xresources
* externalpipe

## Requirements

* Xlib
* cairo
* FontConfig
* FreeType2

## Installation

Edit config.mk to match your local setup (st is installed into the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if necessary as root):

```sh
make clean install
```

## Running st

If you did not install st with make clean install, you must compile the st terminfo entry with the following command:

```sh
tic -sx st.info
```

See the man page for additional details.

## Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
