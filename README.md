lightorgan
==========

A light organ that converts MIDI into lighting changes on an LED strip, based on Arduinio.

At the moment this is just a test sketch. More will come soon.

Usage
-----

Install the [Arduino SDK][sdk] and [ino][ino], then:

1. `ino build`
2. `ino upload`

Resources
---------

There's info about reading MIDI data over USB with the Arduino acting as the host in a few places around the web.

- [Circuits@Home][cah]
- [Collin's Lab][collin]
- [USB MIDI Driver for Arduino USB Host Shield][usbhmidi]
- Project report at [Electronic Delectables][delect]
- Becoming a class-compliant USB MIDI device (but not a host) can be achieved
  using [HIDUINO][hiduino]

[sdk]: http://arduino.cc/en/main/software
[ino]: http://inotool.org
[cah]: http://www.circuitsathome.com/mcu/interfacing-midi-devices-with-arduino-using-usb-host-shield
[collin]: http://makezine.com/2010/11/30/usbhacking/
[usbhmidi]: https://github.com/YuuichiAkagawa/USBH_MIDI
[delect]: http://electronicdelectables.blogspot.com/2011/02/lunch-project-midi-keyboard-and-usb.html
[hiduino]: https://github.com/ddiakopoulos/hiduino
