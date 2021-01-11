# For future reference

- I have just edited the planck's default keymap.c for brevity.


# Installation

1. Setup qmk build environment
    - sudo pacman -S arm-none-eabi-newlib
    - python -m pip install --user qmk
    - make git-submodule
2. Compile firmware
    - CFLAGS="-Wno-error=deprecated" make planck/rev6:default:dfu-util
 
# Editing Keymap

- Edit keyboards/planck/keymaps/default/keymap.c
