ArduinoEthernet
===============

A simple sketch for turning on led's,reading temperature from the analog sensor and displaying it on the browser.


===============

#### IRremote Library :

http://www.righto.com/2009/08/multi-protocol-infrared-remote-library.html

Connect the Infrared LED to the pin 3.


#### Wiring : 

4,5,6 - Digital Out/ LED

A2 - Temperature Sensor LM35

A3 - LDR 

#### Usage : 

Change the Ethernet Settings according to your default gateway

LED 1 ON : 
http://ArduinoIpaddress/?1

LED 1 OFF : 
http://ArduinoIpaddress/?2

LED 2 ON : 
http://ArduinoIpaddress/?3

LED 2 OFF : 
http://ArduinoIpaddress/?4

LED 3 ON : 
http://ArduinoIpaddress/?5

LED 3 OFF : 
http://ArduinoIpaddress/?6

You can add new cases in the switch statement for controlling more pins or adding new sensors.
When an LED is turned On or Off the status is update in the value. 
This can be used to check the state of the led to make real time applications that are in sync with each other.



#### LED STATUS : 

http://ArduinoIpaddress/?7
http://ArduinoIpaddress/?8
http://ArduinoIpaddress/?9

The status of the led's can be obained from here. If the LED is on you get 1 if it is off you get 0.

#### Sensor Details :


##### Temperature Sensor
http://ArduinoIpaddress/?T

##### LDR Sensor
http://ArduinoIpaddress/?L

Add the code needed to obtain the sensor details inside the switch case,it gets executed when the case is passed and provides the detail on the web page. 












