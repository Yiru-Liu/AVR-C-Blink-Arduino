## AVR C LED Blink on an Arduino Uno

This is an example of uploading AVR-C code to the Arduino Uno.

### Instructions

In the Makefile, change the serial port for `PROGRAMMER ARGS` to the serial port that the Arduino connects to. Find which port name the Arduino connects to from the Arduino IDE by checking under Tools &rarr; Serial Port.

Then, to compile and upload, open a terminal window in the directory and enter `make flash`.

