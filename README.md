# 40% Keeb Firmware

If you'd like to get started developing your own keyboard firmware check out the QMK documentation.

QMK docs: https://docs.qmk.fm/#/newbs_getting_started

---


This software is for my Plank and Levinson 40% keyboards I'm using for on-the-go software development. I prefer to have my symbols on my home row and I use curly braces more than square brackets so I'm swapping their shifted state.

To modify my firmware merge my qmk_firmware folder into yours and make any necessary edits to the files provided

To flash my firmware onto your device you can:
- download the provided bin in the qmk_firmware directory and follow the qmk toolbox's docs
- merge the qmk_firmware directory into yours and follow the QMK CLI docs and run `qmk compile -kb planck/rev6 -km timortho`
- use the json2c command in the CLI with the provided json and run the same command

To preview my firmware layout use the provided json on the [qmk configurator](https://config.qmk.fm/#/planck/rev6/LAYOUT_planck_grid), or view the c here, or look at the images below.

Images to be provided at a later date. LOL