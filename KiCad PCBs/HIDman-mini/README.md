[Home](/README.md)
# PCB: HIDman-mini

### Notes:
- **WARNING!** Make sure you install the CH559 IC in the correct orientation!  There are three dots, making it confusing at a glance (as me how I know!)
- **WARNING!** Make sure you install the USB port(s) in the correct orientation!
- **WARNING!** Double and Triple check your PS/2 cable pinout to make sure you don't feed 5V where it shouldn't go!

> ![Profile](https://github.com/serisman/HIDman-mini/blob/main/pictures/HIDman-mini%20-%20Side.jpg?raw=true)

> ![Soldered](https://github.com/serisman/HIDman-mini/blob/main/pictures/HIDman-mini%20-%20Top%20&%20Bottom.jpg?raw=true)

### Schematic
- USB port P1 (on bottom side) is required for loading code, and can be used for USB keyboard/mouse (including keyboard/mouse combo wireless adapters).  It can be installed in the middle of the PCB if USB port P2 is not installed.
- USB port P2 (on top side) is optional, but can be installed if a 2nd USB port is needed.  If installed, USB port P1 will have to be lowered a bit.
- Hold down SW1 while plugging USB port P1 into computer to force bootloader.
- Extra-A and Extra-B are not used for anything (yet).  Therefore R5,R6,R11,R12 are not needed.
- R1,R2,R7,R8 are probably not needed.
- Resistors are 0603
- Capacitors are 0603 (100n) and 0805 (3u3+)
- RN1/RN2 are not actually resistor networks.  They are providing the top/bottom solder pads.
- RN3 is 1k (or whatever works with choosen RGB LED)
> ![Schematic](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-mini/output/Schematic.png?raw=true)

### Soldered PCB
> ![Top](https://github.com/serisman/HIDman-mini/blob/main/pictures/HIDman-mini%20-%20Top.jpg?raw=true)
> ![Bottom](https://github.com/serisman/HIDman-mini/blob/main/pictures/HIDman-mini%20-%20Bottom.jpg?raw=true)

### Raw PCB
> ![PCB Top](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-mini/output/PCB%20Top.jpg?raw=true)
> ![PCB Bottom](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-mini/output/PCB%20Bottom.jpg?raw=true)
