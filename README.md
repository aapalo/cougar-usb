# Cougar USB

Features:
- Can be used to convert a TM Cougar Throttle into a USB device, or as a stand-alone button box.
- Several boards can be daisy-chained via the 1x5 pin socket J11.
- The dimensions of the PCB are 112mm * 37mm.

v1.0 errata:
- Pro micro pin 9, PM_C7, should be PM_D7

This repository has been forked from <https://github.com/aapalo/buttonbox>

----

The required components include:
- Arduino board, Pro Micro 5V/16MHz ATmega32U4
- SMD resistors, 10k Ohm, 0805
- SMD capacitors, 470nF, 0805
- 2x8 pin header, 2.54mm pitch

Add also these components if additional buttons or switches are wanted:
- Shift register, 74HC165N, DIP-16
- Buttons/switches
- Jumper wires for the buttons/switches
- Pin sockets and/or headers, 2.54mm pitch

----

The recommended software to program the Pro Micro is MMJoy2:
<https://simhq.com/forum/ubbthreads.php/topics/3899105/mmjoy-mmjoy2-build-your-own-usb-controller>

When used as a stand-alone button box, the board should fit inside a Hammond [1591C*](1) or a [1591XXC](2) enclosure.

[1]: <http://www.hammondmfg.com/dwg2.htm>
[2]: <https://www.hammfg.com/part/1591XXCBK>
[3]: <http://www.hammondmfg.com/dwg2XX.htm>

----

[//]: # (Todo: add pictures of a soldered version)

The schematic, with some of the planned DCS key bindings visible:
![](./pics/schema.png)

Top side, with the 3d view and layout view:
![](./pics/front_3d.png)
![](./pics/front_layout.png)

Bottom side, with the 3d view and layout view:
![](./pics/back_3d.png)
![](./pics/back_layout.png)

Both the top and bottom layer visible:
![](./pics/layout.png)
