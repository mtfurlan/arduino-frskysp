# arduino-frskysp
This library is for transmitting Frsky SmartPort stuff from an esp32 using HardwareSerial.

The main changes from upstream are to use HardwareSerial instead of SoftwareSerial,
and to swap the pin between RX and TX using `setPins` when transmitting,
because I had issues when they were the same pin.

WARNING: I didn't touch the examples so they don't work right now.

---


FrskySP (SmartPort) protocol library for Arduino - Arduino 1.5 compliant repository of [frsky-arduino](https://github.com/jcheger/frsky-arduino)

This library is in beta stage. All known sensors were tested and seem to work.

# documentation
Documentation was removed out of the repository. It is available on: https://www.ordinoscope.net/static/arduino-frskysp/docs/html/

You can also build it this way (must install doxygen obviously)

````sh
 cd src
 doxygen
````

The documentation will be built in "docs", at the root of the library.
