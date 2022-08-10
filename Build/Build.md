# How to build a GeomorphPi

In this section there is a guide on how to build the basic GeomorphPi platform from which additional functions can be added at your own discretion.




## Step 1 - Raspberry Pi

Using a Raspberry Pi Zero as a base, it can either come headless or with soldered on pins. For ease of use, chose with pins. However, significant savings can be made using headless as long as you are able to solder the pins on yourself.

Familiarise yourself with the layout (available [Here](https://picockpit.com/raspberry-pi/everything-about-raspberry-pi-zero-2-w/)) and the GPIO pinout (available [Here](https://pi4j.com/1.2/pins/model-3a-plus-rev1.html)).





## Step 1 - Raspberry Pi

Using a Raspberry Pi Zero as a base, it can either come headless or with soldered on pins. For ease of use, chose with pins. However, significant savings can be made using headless as long as you are able to solder the pins on yourself.






A RaspberryPi can boot into a number of OS, based upon the Debian OS. For GeomorphPi we chose the RaspberryPi OS Lite (available [Here](https://www.raspberrypi.com/software/operating-systems/)).

To install the OS onto your SD card you will need to format and then transfer the OS to the card. To format the SD card first download a SD card formatiing software (available [Here](https://www.sdcard.org/downloads/formatter/)) and format the SD card. **Warning this will erase all data on the SD card**

To place the OS onto the now blank SD card you will need a software package such as balenaEtcher (available [Here](https://www.balena.io/etcher/)).

In balenaEtcher select the target drive as the SD card and the file as the RaspberryPi OS. Depending on the SD card this should take no longer than 5 minutes.
