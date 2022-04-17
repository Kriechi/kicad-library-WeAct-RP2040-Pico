# KiCad Footprint and Symbol for WeAct RP2040 Pico module

This repository contains KiCad 6 footprint and symbol libraries for the WeAct RP2040 Pico module (like the Raspberry Pi Pico board, but with USB-C and minor differences on used GPIO pins).

The KiCad symbol contains all alternative pin assignments so you can select which function each pin should serve.

The KiCad footprint is linked to a 3D model: `WeAct-RP2040-Pico.step`, which is imported into this repository for convenience from the official [WeAct RP2040 repository](https://github.com/WeActTC/WeActStudio.RP2040CoreBoard).

See also official documentation of the module at: https://github.com/WeActTC/WeActStudio.RP2040CoreBoard/tree/master (see both branches!).

See this Raspberry Pi forum post about the module: https://forums.raspberrypi.com/viewtopic.php?t=326528

## Installing this library

You can install this library via the KiCad 6 **Plugin and Content Manager**:

* Get the latest archive [here](https://github.com/Kriechi/kicad-library-WeAct-RP2040-Pico/archive/refs/heads/main.zip)
* Open your KiCad main window, select the **Plugin and Content Manager**
* Click the **Install from File...** button
* Select the just downloaded archive file
* Add the following entries to your Global or Project footprint & symbol libraries
  * **Manage Footprint Libraries...** from the menu bar, and add a new entry
    * Nickname: WeAct-RP2040-Pico
    * Library Path: `${KICAD6_3RD_PARTY}/footprints/com_github_kriechi_kicad-library-WeAct-RP2040-Pico/WeAct-RP2040-Pico.pretty`
  * **Manage Symbol Libraries...** from the menu bar, and add a new entry
    * Nickname: WeAct-RP2040-Pico
    * Library Path: `${KICAD6_3RD_PARTY}/symbols/com_github_kriechi_kicad-library-WeAct-RP2040-Pico/WeAct-RP2040-Pico.kicad_sym`
