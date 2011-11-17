USB to UART/485 Interface
=========================


This project is a simple USB UART/485 interface based on the FTDI FT232
controller chip.

The board feature two LEDs for bus activity, a 2x3 2.54mm strip with TTL UART
signals and a 485 transceiver with a 8P8C connettor compatible with both
generic 8P8C connectors and Neutrik Ethercon connectors.

License
-------

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Contents
--------

    COPYING     text version of the GPL
    README      this file
    hardware/   source directory for the hardware design files

Firmware
--------

No firmware is needed for this design. FTDI drivers are already available on
most GNU/Linux distributions.

Hardware
--------

All hardware files (schematic, layout and libraries) are in CadSoft Eagle
format.

The PCB is designed to work at 3.3V for UART signal/485 levels, but can be
easily modified to work at 5V by bypassing the 3.3V linear regulator and
mounting a standard 5V 485 transceiver.
