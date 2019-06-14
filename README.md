## Adafruit DPI Kippah PCB

<a href="http://www.adafruit.com/products/2453"><img src="assets/2453.jpg?raw=true" width="390px"></a>&nbsp; 
<a href="http://www.adafruit.com/products/2454"><img src="assets/2454.jpg?raw=true" width="390px"></a><br/>
Click the image or links below to go to a specific product in the Adafruit shop.

PCB files for the Adafruit Adafruit DPI Display Kippah for Raspberry PI. Format is EagleCAD schematic and board layout
* TFT & Resistive Touch support https://www.adafruit.com/product/2453
* TFT Display Support Only https://www.adafruit.com/product/2454

### DESCRIPTION
A TFT panel connected to a Raspberry Pi without the use of an HDMI decoder? What is this sorcery??? It's the DPI Kippah from Adafruit! This HAT-like* board snaps onto a Raspberry Pi B+, A+, Pi 2, Pi 3 or Zero and with a little software configuration, allows you to have what normally would go out the HDMI port come up on a nice little flat screen. *Its not technically a HAT due to the lack of an on-board EEPROM, but its the same shape as a Pi HAT and its a covering of sorts, so we call it a kippah

This is the Kippah with resistive touch support. If you don't need a touchscreen then here's our super low-cost version of the Kippah without the USB touchscreen capability.

Compared to our lovely HDMI backpacks, you don't have the extra cost or expense of an HDMI encoder/decoder. And you get a nice ultra-fast 18-bit color display with optional touch support. We tested it and it works great with our 5" and 7" displays at 800x480. This display is 'native' so it gets all the graphics accelleration capabilities, instant refresh, etc. you would get from an HDMI display

OK so, exciting right? But, what's the catch? The catch is this add on board uses nearly every pin available on the Raspberry Pi and those pins are hardcoded, they cannot be moved or rearranged. The pins used are GPIO 2 through 21 inclusive. That means you don't get the UART RX/TX pins (no console cable) and you don't get the standard user I2C pins, the EEPROM I2C pins, or hardware SPI pins. You do get to use pins #22, #23, #24, #25, #26 and #27, and the USB ports are fine to use too.

The other catch is that this display replaces the HDMI/NTSC output, so you can't have the DPI HAT and HDMI working at once, nor can you 'flip' between the two.

Also, there's no PWM's available so you can't have precision backlight control unless you somehow rig up an external PWM generator with a 555 or something. Finally, we did test this setup with a straight-up Raspbian and after the software installs, it works great. However, we don't guarantee it will work with any other Raspberry Pi operating system or setup.

That said, if you dont need all of the Pi GPIO, its very easy to add a high quality display. Pick and choose whether you want a touch-screen or not, then choose the size of the display - 5" or 7" is best. You can also grab an FPC extension board and extend the display away from the Pi. For power-users, this is a very nice little accessory

Comes as one fully assembled and tested DPI Kippah circuit board. You may need a soldering iron to adjust the backlight by soldering closed a PCB jumper (check the tutorial on this).TFT display, USB micro-B cable, FPC extension cable, bent wire stand, and Raspberry Pi not included (but we do carry them in the shop!) Check out our tutorial on how to install the device tree overlay and configure the backlight

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit.com](https://www.adafruit.com)!

Creative Commons Attribution, Share-Alike license, check license.txt for more information All text above must be included in any redistribution - 
See license.txt for more information.
