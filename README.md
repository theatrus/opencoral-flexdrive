# OpenCoral FlexDrive High Current LED Driver

LM3404(HV) based dual LED driver with optional MCU supervision / dimming
support.

![product](https://raw.githubusercontent.com/theatrus/opencoral-flexdrive/master/flexdrive_board.png)

# Features

 * Dual LM3404HV drivers and all power switching circuitry.
 * Runs on up to 60V input, 24-48VDC suggested.
 * Up to 1.5A per LED chain
 * On board MCU and power supply for dimming control of each channel
   (ATmega8)
 * RS485 transceiver and two RJ-12 jacks for control signals from a
   controller.
 * MCU is optional, dimming control can be done via external pins (PWM)

# License

CC-SA-NC 3.0.

See LICENSE.txt

# Design Status

This design was built and is in operation.

## Boards

Available on OSHPark:
http://oshpark.com/shared_projects/ymYU4l9N

# Files available

The original design is available as Eagle 6.x (XML-based) design
files, in the eagle/ directory.

Gerber files from the Eagle board file are made available in the
gerber/ directory.

Schematic PDF is available in the root of this repository.



