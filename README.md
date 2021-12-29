# dmenu - dynamic menu

dmenu is an efficient dynamic menu for X.

**Note: I have stopped development on this fork for now in favour of Rofi. I may continue it sometime.**

My rofi config: [jtbx/dotfiles/.config/rofi/config.rasi](https://github.com/jtbx/dotfiles/blob/main/.config/rofi/config.rasi)

# Requirements

In order to build dmenu you need the Xlib header files.

My config also requires the JetBrains Mono font.

On Arch Linux, you can install that package with `sudo pacman -S ttf-jetbrains-mono`.

# Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


# Running dmenu

See the man page for details.
