pi-servo
========

PWM Servo Control for Raspberry Pi running Xenomai realtime GNU/Linux


Credits & License
=================

Written by Simon Finne <simon.finne@loopon.com>

Feel free to use as you want, on your own responsibility. The code is provided
"as is", no warranty.

Thank you to Gert van Loo & Dom for GPIO example code:
http://elinux.org/RPi_Low-level_peripherals#GPIO_Driving_Example_.28C.29


Description
===========

Extremely simple library for generating PWM (Pulse Width Modulated) signals on
the Raspberry PI GPIO pins, as used by common r/c servos.


Quick-start
===========

* Get & install Xenomai for the Raspberry Pi: TODO: UPDATE THIS
  http://powet.eu/2012/07/25/raspberry-pi-xenomai/

* Connect the signal cable of a servo to GPIO07 (pin 26) TODO: ADD IMAGE IN THIS README
http://elinux.org/RPi_Low-level_peripherals#General_Purpose_Input.2FOutput_.28GPIO.29

* Connect external power source to your servo and ensure you share the ground with
  your Raspberry Pi (pin 6)

* Add the LD_LIBRARY_PATH -> export LD_LIBRARY_PATH=/usr/xenomai/lib
* Run "make examples" and then execute "examples/move-servo-7"


