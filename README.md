
Simon Kit from Firefly Electronix
=================================

<p align="left">
  <img src="SimonKit_light-up slideshow.jpg" width="350"/>
</p>

Setup the Arduino IDE
---------------------
If you want to reprogram the Simon Kit, you will need to add it to the boards file on your computer. This is located under C:\Program Files (x86)\Arduino\hardware\arduino\avr

<p>Scroll to the bottom and add the lines of code from the boards.txt file. You will also need to add the bootloader file ATmegaBOOT_Simon.hex. This is located in the bootloaders folder here C:\Program Files (x86)\Arduino\hardware\arduino\avr\bootloaders\atmega</p>

<p>The Simon Kit will now show up in the Arduino IDE as an option to choose under Tools/Board:. Keep in mind that this design uses the 8MHz internal clock as opposed to the 16MHz clock on the Arduino UNO.</p> 

Pins available
--------------

The LEDs are connected to pins 3, 5, 10, and 13 (colors may be different on yours depending on how you assembled it).

The Buttons are connected to pins 2, 6, 9, and 12

All of the analog pins are also available to use to connect sensors just as you would on an Arduino Uno.

If you want to go back to the original Simon firmware download the source code here.

