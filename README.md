# dmenu - dynamic menu
dmenu is an efficient dynamic menu for X.

## Requirements
In order to build dmenu you need the Xlib header files.

## Installation
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install

## Todo
- instant immer und nur mit flag aus?
- instant fuzzy machen 
- dynamic options installiert testen
- fuzzyhighlight farben in xresources
- fuzzyhighlight multiple-selection sehen hässlich in Kombination aus

## Später noch patchen
- [incremental](https://tools.suckless.org/dmenu/patches/incremental/)
- [non_blocking_stdin] (https://tools.suckless.org/dmenu/patches/non_blocking_stdin/)
- [password] (https://tools.suckless.org/dmenu/patches/password/)
