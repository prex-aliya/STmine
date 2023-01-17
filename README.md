# STmine is a version of [st](https://st.suckless.org/) that I have modified.
<!--
<div class="aside">
    <h2>MyST - This is my version of <a href="https://st.suckless.org/"> st <a>.</h1>
</div>
-->



## Current Patches

- [alpha](https://st.suckless.org/patches/alpha/)
- [font2](https://st.suckless.org/patches/font2/)


## TODO:

- Plugins
    - [autocomplete](https://st.suckless.org/patches/autocomplete/)
    - [boxdraw](https://st.suckless.org/patches/boxdraw/)
        - gape less alignment
    - [colors_at_launch](https://st.suckless.org/patches/colors_at_launch/)
    - [cyberpunk-neon](https://st.suckless.org/patches/cyberpunk-neon/)
    - [keyboard_select](https://st.suckless.org/patches/keyboard_select/)
    - [ligatures](https://st.suckless.org/patches/ligatures/)
    - [sync](https://st.suckless.org/patches/sync/)
    - [vim_browse](https://st.suckless.org/patches/vim_browse/)
        - may replace keyboard select
    - [vertcenter](https://st.suckless.org/patches/vertcenter/)
    - [scrollback](https://st.suckless.org/patches/scrollback/)
    - [copyurl](https://st.suckless.org/patches/copyurl/)





# Original README

## st - simple terminal

ST is a simple terminal emulator for X which sucks less.


## Requirements

In order to build st you need the Xlib header files.


## Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


## Running st

If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

## Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

