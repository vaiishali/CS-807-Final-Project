# CS-807-Final-Project

## Remotely monitored Soil Moisture Detection System

### Overview

This device detects humidity of the soil and then the data is sent to the server with the help of Wi-Fi module.
This data can then be accessed remotely from anywhere around the world.
It is perfect device to build an automatic watering system or smart garden where you can control your garden remotely.

![Project picture.jpg](https://github.com/vaiishali/CS-807-Final-Project/blob/master/img/Project%20picture.jpg)

![Circuit Picture.jpg](https://github.com/vaiishali/CS-807-Final-Project/blob/master/img/Circuit%20Picture.jpg)


Requirements and Materials
============

* **/src** - Code.ino
* **/hardware** - model.fzz
* **/build** - calibrate.ino.
* **/libraries** - <ESP8266WiFi.h>
* **/examples** - code.ino, calibrate.ino 
* **/img** -  4 x images
* **/LICENSE** 
* **/README.md** 

Requirements and Materials
============

Dependencies:
* ESP8266 Wifi module https://learn.adafruit.com/adafruit-feather-huzzah-esp8266/using-arduino-ide

Bill of Materials:
* 1x RGB
* 1 x Moisture sensor
* 1 x breadboard
* 1 x  Adafruit Feather HUZZAH ESP8266
* multiple jumper wires

Build Instructions
==================

![BREADBOARD6_bb.jpg](https://github.com/vaiishali/CS-807-Final-Project/blob/master/img/BREADBOARD6_bb.jpg)

![SCHEMATICS6_schem.jpg](https://github.com/vaiishali/CS-807-Final-Project/blob/master/img/SCHEMATICS6_schem.jpg)


Firmware Installation
=====================

To give instructions, Arduino IDE (Computer Application) is used to upload the code to the device.
The ESP8266 is connected to computer by a USB cable. <ESP8266WiFi.h> library is used to programm the device.



Usage
=====
To use the device, follow the given steps: 

* Upload the code to the device. 
* Wait for it to connect with local wifi. 
* Put the soil moisture sensor in the soil 
* Go to webserver link to view the moisture level
* refresh link to view updated results


Team
=====
The build team consists of: 
* Vaishali -- Project designing, Coding, and project building.


Credits
======= 

* Trevor Tomesh -- Borrowing electronic components, advice on coding.


