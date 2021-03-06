Making a Robo-Chef
==================

> We can build it. We have the technology.

-- _Some Awesome TV Show_

## :fork_and_knife: It's Time... to make a Robo-Chef.:fork_and_knife:

Main Ingredients:

1.  Adafruit TMP006 Infrared Thermopile Sensor
  * contactless temperature sensor -- can watch the water boil
2.  Internet Connection
  * For updating a server, and possibly tweeting
4.  Raspberry Pi Camera
  * Open CV capabilities (maybe we want to wait until the beef, or whatnot, changes color)
3.  High-Torque Servo Motors
  * For turning knobs on the stove to the off position.


### BOM

| Item | Number | Total Cost | Link To Supplier |
| :--- | :---: | :---: | :--- | 
| Contactless Temperature Sensor | 1 | $14.95 | [link](http://www.adafruit.com/products/1296) |
| Raspberry Pi | 1 | $39.95 | [link](http://www.adafruit.com/products/998) |
| Raspberry Pi Camera | 1 | $29.95 | [link](http://www.adafruit.com/products/1367) | 
| Arduino Compatible Board | 1 | $11.48 | [link](http://www.ebay.com/itm/Arduino-UNO-R3-board-with-DIP-ATmega328P-Development-Board-/271320440356?pt=LH_DefaultDomain_0&hash=item3f2bf55e24) | 
| Wires and Stuff | 1 | $7.25 | [link](http://www.ebay.com/itm/70PCS-Breadboard-Jumper-Cable-Wire-PCB-Protoboard-Test-Circuit-Board-400-Point-/400614957426?pt=LH_DefaultDomain_0&hash=item5d46832172) |
| Batteries? | ? | ? | not included?? |

In any case with these and a chassis of some sort of battery, the electrical is pretty much taken care of.

Now for the mechanical challenge, we will need to create a chassis which can peer over the food and "see" with IR what the temperature, texture, and color of the food is.





> I for one, welcome our new Robo-Chefs.

-- _what each of us is thinking right now_


## Credits and Original README.txt

This is a library for the Adafruit TMP006 Infrared Thermopile Sensor

Designed specifically to work with the Adafruit TMP006 Breakout 
  ----> https://www.adafruit.com/products/1296

These displays use I2C to communicate, 2 pins are required to interface
Adafruit invests time and resources providing this open source code, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Check out the links above for our tutorials and wiring diagrams 

Adafruit invests time and resources providing this open source code, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.  
BSD license, all text above must be included in any redistribution

To download. click the DOWNLOADS button in the top right corner, rename the uncompressed folder Adafruit_TMP006. Check that the Adafruit_TMP006 folder contains Adafruit_TMP006.cpp and Adafruit_TMP006.h

Place the Adafruit_TMP006 library folder your <arduinosketchfolder>/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE.
