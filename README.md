
# Open-hardware knob system for acceleration control operations #

## Description

The hardware has been structured on a PCB where are mounted 9 keys and a mechanical encoder.
The keys are used to simulate, at the firmware level, the pressure of one keyboard button or a combination of them. 
Each key is equipped with anti-bounce circuitry and ade-quate ESD protection to prevent a malfunction or breakdown 
of the electronics.
The microcontroller is devoted to managing the USB HID communication. 
To have multiple options in terms of hardware solutions for the microcontroller, the PCB has been realized to be 
compatible with both ARM STM32 microcontroller and Teensy LC module.

## License

Copyright INFN-LNL 2020.
This documentation describes OHKS_WFP hardware and is licensed under the
CERN OHL v. 1.2.
You may redistribute and modify this documentation under the terms of the
CERN OHL v.1.2. (http://ohwr.org/cernohl). This documentation is distributed
WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF
MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable
conditions
