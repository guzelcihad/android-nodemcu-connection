# android-nodemcu-connection
This is a basic led blink example using android and esp8266 nodemcu. The main purpose of this application is how to connect android device to esp8266 nodemcu lolin. I wanted to show send and get data from android to esp8266 nodemcu.I hope it will be useful for you.

### Requirements

  * Breadboard
  * LED
  * Jumper Cable
  * Android Studio
  * Arduino IDE
  * A Wifi Network 
 
### Usage

  * You must use D7 pin(in Arduino IDE Digital 13 pin)
  * Connect LED to this pin
  * Open ```nodemcu.ino```using  Arduino IDE,change ```ssid``` and ```password``` for your network 
  * Then install this file to nodemcu module using usb cable
  * Open Android Studio and run the app

### Important Files

 * ```MainActivity.java```
 * ```activity.main```
 * ```nodemcu.ino```
 
### Nodemcu Circuit Image
  ![alt tag](https://github.com/cihadguzel/android-nodemcu-connection/blob/master/arduino/NodemcuLed.png)
