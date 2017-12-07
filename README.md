# modular_device_serial_terminal

Authors:

    Peter Polidoro <polidorop@janelia.hhmi.org>

License:

    BSD

## Setup Host Computer

### Controlling Arduino-like Modular Device Servers

#### Install Arduino and Teensyduino on your Host Machine

[Setup Arduino](https://github.com/janelia-arduino/arduino_setup)

## Serial Terminals

## Arduino IDE

Connect a USB cable from the host computer to the modular device. Open
the Arduino IDE and select the appropriate serial port. Open the
Arduino IDE Serial Monitor and select "Newline" and "115200
baud". Type a question mark ? into the input field and press Enter or
click Send to get started.

## Cutecom

Connect a USB cable from the host computer to the modular device. Open
cutecom and enter the appropriate serial port. Select 115200, 8, 1,
NONE, no handshake, and open for both reading and writing. Select LF
line end. Open device. Type a question mark ? into the input field
and press Enter to get started.
