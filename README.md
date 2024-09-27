# HIDman-mini
A USB keyboard/mouse to PS/2 (or AT, Serial) computer adapter.

Based on and compatible with: [HIDman](https://github.com/rasteri/HIDman) by [rasteri](https://github.com/rasteri)
 - In the Makefile, make sure the correct `BOARD_TYPE` is selected and then make sure `OSC_TYPE = OSC_INTERNAL` is enabled and `OSC_TYPE = OSC_EXTERNAL` is disabled.  Re-compile and flash the firmware following the instructions found in the HIDman firmware.
   - For the -mini: Choose `BOARD_TYPE = BOARD_AXP` (for ps/2 and serial support), or `BOARD_TYPE = BOARD_MINI` (for just ps/2 support).
   - For the -micro: Choose `BOARD_TYPE = BOARD_MICRO` (only has ps/2 support).
     - Optionally switch to `BOARD_OPTIONS = OPT_SWAP_KBD_MSC` to make it a bit easier to wire up a combo ps/2 port.

### PCBs
- [HIDman-mini](KiCad%20PCBs/HIDman-mini/)
- [HIDman-micro](KiCad%20PCBs/HIDman-micro/)
- [DB9-to-TTL](KiCad%20PCBs/DB9-to-TTL/)

### 3D Printer Models
- [Cover for HIDman-mini](3D%20Printer%20Models/HIDman-mini/)
- [Shell for DB9-to-TTL](3D%20Printer%20Models/DB9-Shell/)

![Finished](https://github.com/serisman/HIDman-mini/blob/main/pictures/HIDman-mini/Finished.jpg?raw=true)

### Schematics
(for HIDman-mini)
![Schematic](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-mini/output/Schematic.png?raw=true)

(for DB9-to-TTL)
![Schematic](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/DB9-to-TTL/output/Schematic.png?raw=true)

NOTE: Remember to cross-over TxD <--> RxD, and RTS <--> CTS when connecting the two PCBs!

### Optional Configuration: Combo PS/2 Keyboard/Mouse Connector
(for computers that support it)
![Combo PS/2 Keyboard/Mouse](https://github.com/serisman/HIDman-mini/blob/main/pictures/HIDman-mini/Combo%20PS2%20KB%20MS.jpg?raw=true)
![Combo PS/2 Keyboard/Mouse on PC](https://github.com/serisman/HIDman-mini/blob/main/pictures/HIDman-mini/Combo%20PS2%20KB%20MS%20on%20PC.jpg?raw=true)

### Copyright and License:
- Copyright (C) 2022 - serisman (github@serisman.com)
- License: [GPL v3 (or later)](LICENSE)
