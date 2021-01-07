# 40% Keeb Firmware

![Planck keyboard](/img/planck.jpg)
---
If you'd like to get started developing your own keyboard firmware check out the QMK documentation.

QMK docs: https://docs.qmk.fm/#/newbs_getting_started

---


This software is for my Plank and Levinson 40% keyboards I'm using for on-the-go software development. I prefer to have my symbols on my home row and I use curly braces more than square brackets so I'm swapping their shifted state.

To modify my firmware merge my qmk_firmware folder into yours and make any necessary edits to the files provided

To flash my firmware onto your device you can:
- download the provided bin in the qmk_firmware directory and follow the qmk toolbox's docs
- merge the qmk_firmware directory into yours and follow the QMK CLI docs and run `qmk compile -kb planck/rev6 -km timortho`
- use the json2c command in the CLI with the provided json and run the same command

To preview my firmware layout use the provided json on the [qmk configurator](https://config.qmk.fm/#/planck/rev6/LAYOUT_planck_grid), or view the [keymap.c here,](/qmk_firmware/keyboards/planck/keymaps/timortho/keymap.c) or look at the images below.

## Layer 0 
is a standard QWERTY layout. the Raise and Lower keys shift layers to layer 4 and 3 respectively

![Planck keyboard layer 0](/img/planckLayer0.PNG)

## Layers 1 and 2 
are Colemak and Dvorak, alternative layouts to QWERTY.

## Layer 3
contains a num bar across the top and fkeys in the lower left. After my mods to layer 4 I don't have much use for this layer so I may change it to a num pad layer or a layer holding boiler plate scripts.

![Planck keyboard layer 3](/img/planckLayer3.PNG)

## Layer 4
contains a num row with shiftable symbols along the top row. Home row contains my most used symbols for development, and a reverse shifted curly/square bracket key as I use curly far more often than square brackets.

![Planck keyboard layer 4](/img/planckLayer4.PNG)

## Layer 5
is Plover layout, a layout for stenographers. I have no intention of using this or changing it as I haven't needed it yet.

## Layer 6
contains a ton of qmk specific scripts that modifie hardware features this is for the most part unchanged from the rev6 firmware with the exception of the added fkeys along the border of the keymap.

![Planck keyboard layer 6](/img/planckLayer6.PNG)


