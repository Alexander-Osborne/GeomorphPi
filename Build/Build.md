# How to build a GeomorphPi

In this section there is a guide on how to build the basic GeomorphPi platform from which additional functions can be added at your own discretion. It would be up to the builder to decide on the casing required to accomodate any batteries of attatchements. A high IP rating is recommended.




## Step 1 - Raspberry Pi

Using a Raspberry Pi Zero as a base, it can either come headless or with soldered on pins. For ease of use, chose with pins. However, significant savings can be made using headless as long as you are able to solder the pins on yourself.

Familiarise yourself with the layout (available [Here](https://picockpit.com/raspberry-pi/everything-about-raspberry-pi-zero-2-w/)) and the GPIO pinout (available [Here](https://pi4j.com/1.2/pins/model-3a-plus-rev1.html)).

These will be how attatchments can communicate with the Pi.




## Step 2 - Power

Power can be either supplied via the micro USB or via the 5 V pins. Fundamentally the voltage should be 5 V and a current supplied in excess of 1 Amp preferably.

Power when used in the field will need to be supplied by battery. NiMH or lead acid batteries can be used, and a USB voltage step down converter used.


## Step 3 - Power saving

As a data logger, the GeomorphPi can be left on constantly, or be timed to boot on and off to make the batteries last longer. A timer board (available [Here](https://shop.pimoroni.com/products/witty-pi-3-mini-realtime-clock-and-power-management-for-raspberry-pi?variant=39447710662739)) can be used for this function. Full instructions on how to use the timer are found on thr website.


