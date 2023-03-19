# PCB for the Rotary Head Controller
This repository is a part of a larger project. The description of it can be found in the [rotary-head-software](https://github.com/JanOlencki/rotary-head-software) repository.

## Features
* Comunication via RS-485 standard (terminating resistor included)
* STM8 microcontroller (SWIM programming interface exposed on pin header)
* One connector (RJ-45) for both communication and power supply
* Stepper motor control using the *Allegro A5977* driver
* Adjustment of the stepper motor current
* Electrostatic discharge protection
* Over-current protection (using a resettable fuse)
* Step down voltage conversion for a digital part (EMI filter included)

## Manufacturing and Assembly 
The PCB is designed to be manufactured on a double-sided FR4 laminate (1.5mm thick) with 35&mu;m thick copper. It's recommended to solder all parts by hand.

## Repository contents
* Schematic
* Board GERBER and Drill files
* Bill of Materials
