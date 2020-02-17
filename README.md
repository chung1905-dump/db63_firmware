# DB63

A 65% keyboard hotswap with RGB that runs ps2avrgb natively, with USB C, RGB underglow and backlight.

* Keyboard Maintainer: QMK Community
* Hardware Supported: DB63 (ATmega32A)
* [Keyboard layout](http://www.keyboard-layout-editor.com/#/gists/dadea703fc8bfc87dc7c480de9f3ef38)

Make example for this keyboard (after setting up your build environment):

    make db/db63:custom

Flashing example for this keyboard ([after setting up the bootloadHID flashing environment](https://docs.qmk.fm/#/flashing_bootloadhid))

    make db/db63:custom:bootloadHID

**Reset Key**: Hold down the key located at *K00*, commonly programmed as *Escape* while plugging in the keyboard. (*All backlight LEDs will flash which indicate the board is in bootloader mode.*)

**Tips**: Combo Caplocks + Return(Enter) will make keyboard reset to bootloader mode

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
