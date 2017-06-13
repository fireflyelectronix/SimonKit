This is the Simon Kit from Firefly Electronix. 

If you want to reprogram the Simon Kit, you will need to add it to the boards file on your computer. This is located under C:\Program Files (x86)\Arduino\hardware\arduino\avr

Scroll to the bottom and add the lines of code from the boards.txt file. You will also need to add the bootloader file ATmegaBOOT_Simon.hex. This is located in the bootloaders folder here C:\Program Files (x86)\Arduino\hardware\arduino\avr\bootloaders\atmega

The LEDs are connected to pins 3, 5, 10, and 13 (colors may be different on yours depending on how you assembled it).

The Buttons are connected to pins 2, 6, 9, and 12

All of the analog pins are also available to use to connect sensors just as you would on an Arduino Uno.

If you want to go back to the original Simon firmware download the source code here.
