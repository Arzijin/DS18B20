# DS18B20 #

Arduino library for the Maxim Integrated DS18B20 1-Wire temperature sensor.

## Usage ##

This library uses the OneWire library, so you will need to have this installed. Get it [here](http://www.pjrc.com/teensy/td_libs_OneWire.html).

In the **OneWire.h** file set `ONEWIRE_SEARCH` to 0 since the search functionality is also implemented in this library (don't do this if you need the search functionality for other 1-Wire devices). CRC must be enabled (choose whichever algorithm you prefer). This may save some space on your Arduino.

For general usage see the included examples.
