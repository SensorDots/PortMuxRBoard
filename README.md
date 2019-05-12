# Port MuxR Arduino Board Libraries

These board files are required to compile the firmware for the SensorDots Port MuxR

## Installation

Install the latest 1.8.6 Arduino version or later (this is required for the latest board manager tools to install).

Add the following URL to the Arduino Boards Manager (File->Preferences):

	https://raw.githubusercontent.com/sensordots/PortMuxRBoard/master/package_m328pb_index.json

Update the Arduino AVR Boards to version 1.6.22 or higher via the Boards Manager (Tools->Boards->Boards Manager). This is important, otherwise the sketch won't compile.

Install the "SensorDots Port MuxR" board via the Boards Manager (Tools->Boards->Boards Manager).

To compile just select SensorDots Port MuxR as the board to build against and the appropriate COM port.

## Change Log

1.1.3 - Initial release based off version 1.1.3 of the https://github.com/watterott/ATmega328PB-Testing libraries.
