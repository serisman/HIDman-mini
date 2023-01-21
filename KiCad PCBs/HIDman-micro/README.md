[Home](/README.md)
# PCB: HIDman-micro

Order from [OSHPARK](https://oshpark.com/shared_projects/RKMXx0oz) or upload [gerber.zip](output/gerber.zip) to your favorite PCB board fabricator.

### Notes:
- **WARNING!** Make sure you install the USB port in the correct orientation!
- **WARNING!** Double and Triple check your PS/2 cable pinout to make sure you don't feed 5V where it shouldn't go!

![Profile](https://github.com/serisman/HIDman-mini/blob/main/pictures/micro/HIDman-micro%20-%20Compared%20to%20PS2%20Cable%202.jpg?raw=true)

### Schematic
- USB port P1 (on bottom side) is required for loading code, and can be used for USB keyboard/mouse (including keyboard/mouse combo wireless adapters).
- Hold down SW1 while plugging USB port into computer to force bootloader.
- Resistors are 0603
- Capacitors are 0603 (100n and 3u3) and 0805 (10u)

**WARNING!** This uses a different pinout than HIDman-mini.  Runtime detection can read P4.7, check if it is LOW or floating, and adjust the PS/2 pins accordingly.

![Schematic](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-micro/output/Schematic.png?raw=true)

### Soldered PCB
![Top](https://github.com/serisman/HIDman-mini/blob/main/pictures/micro/HIDman-micro%20-%20Top.jpg?raw=true)
![Bottom](https://github.com/serisman/HIDman-mini/blob/main/pictures/micro/HIDman-micro%20-%20Bottom.jpg?raw=true)

### 3D Render
![Profile](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-micro/output/3D%20Profile.png?raw=true)
![Top](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-micro/output/3D%20Top.png?raw=true)
![Bottom](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-micro/output/3D%20Bottom.png?raw=true)

### Raw PCB
![Top](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-micro/output/OSHPARK%20Top.png?raw=true)
![Bottom](https://github.com/serisman/HIDman-mini/blob/main/KiCad%20PCBs/HIDman-micro/output/OSHPARK%20Bottom.png?raw=true)
