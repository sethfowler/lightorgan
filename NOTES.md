Hardware
========

1. Arduino Mega2560
2. RGB LED Strip with 2 LEDS per LPD8806 all chained to act as one giant shift register: http://www.adafruit.com/products/306
3. 5V 2A power supply. 2A per meter.


Performance Notes
=================

Refresh (including reading and writing an array) is 800 microseconds per 32 LEDS or one meter using the SPI protocol and the adafruit LPD8806 libraries.
