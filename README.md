# dmenu - dynamic menu

dmenu is an efficient dynamic menu for X.


# Requirements

In order to build dmenu you need the Xlib header files.

My config also requires the Hack font.

On Arch Linux, you can install that package with `sudo pacman -S ttf-hack`.

# Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


# Running dmenu

See the man page for details.
