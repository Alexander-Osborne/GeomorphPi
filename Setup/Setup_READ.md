# How to optimise the OS

In this section there is a guide on how to download and optimise the RaspberryPi OS for use with GeomorphPi. Through a combination of code optimisation and operating system (OS) selection, the end goal is to achieve the fastest boot time.




## Step 1 - Downloading the OS

A RaspberryPi can boot into a number of OS, based upon the Debian OS. For GeomorphPi we chose the RaspberryPi OS Lite (available [Here](https://www.raspberrypi.com/software/operating-systems/)).

To install the OS onto your SD card you will need to format and then transfer the OS to the card. To format the SD card first download a SD card formatiing software (available [Here](https://www.sdcard.org/downloads/formatter/)) and format the SD card. **Warning this will erase all data on the SD card**

To place the OS onto the now blank SD card you will need a software package such as balenaEtcher (available [Here](https://www.balena.io/etcher/)).

In balenaEtcher select the target drive as the SD card and the file as the RaspberryPi OS. Depending on the SD card this should take no longer than 5 minutes.


## Step 2 - First Boot

Inserting the SD card into the RaspberryPi for the first time and booting will load RasperryPi OS. Unlika desktop computer, the system will boot into terminal mode. This will require a keyboard to navigate.

The RaspberryPi will restart at this stage as it expands its file system storage to take up the full capacity of the SD card.

You will be greeted with a login screen. Username: pi and Password: raspberry (these defaults can change with new OS)


## Step 3 - Connecting to the internet

Connecting the RaspberryPi to the internet will enable the easy installation of packages at a later time. This however does not need to be connected to WiFI when used for data collection.

**Type**

*sudo raspi-config*

Select Network and connect as normal to WiFI.


## Step 4 - Update

Update OS by typing

*sudo apt-get update*


## Step 5 - Optimise

Depending on the usage certain features can be disabled to allow faster boots. Follow this link to find out more (available [Here](https://singleboardbytes.com/637/how-to-fast-boot-raspberry-pi.htm))


