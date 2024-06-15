# split72

![split72](https://imgur.com/a/j4D3FPa)

A handwired and 3D printed split 65% layout plus some extra function keys. Swappable body and baseplate. Uses USB-C to carry signals because why not. [I love Omega Strikers.](https://imgur.com/a/F8A3mDl)

* Keyboard Maintainer: [Awedtan](https://github.com/Awedtan)
* Hardware Supported: [WeAct Blackpill (STM32F411)](https://docs.qmk.fm/platformdev_blackpill_f4x1#weact-blackpill-stm32f4x1)
* Hardware Availability: [AliExpress](https://www.aliexpress.com/item/1005001456186625.html)

Make example for this keyboard (after setting up your build environment):

    make split72:default

Flashing example for this keyboard:

    make split72:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
