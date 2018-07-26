# dz60_layout

This repository contains the custom key mappings I've generated for use on the DZ60 PCB.

# Use

Copy the key map file into the appropriate qmk_firmware location for use during compiling and flashing.

* /qmk_firmware/keyboards/dz60/keymaps/custom_keymap

Put the board into reset mode or unplug and plugin while holding <space> + <b>.

Compile and flash the board.

```
sudo make dz60:custom_keymap:dfu
```

## Authors

**Patrick Henson** - initial author and contributor

## License

This project is available as open source under the terms of the [Apache 2.0 Licesnse](https://opensource.org/licenses/Apache-2.0)
