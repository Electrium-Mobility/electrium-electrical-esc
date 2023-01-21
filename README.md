# Electrium ESC V1.0

This is Electrium's version of the Electronic Speed Controller (dubbed the BESC). Heavy reference was from the VESC 4.11 model from here: https://github.com/vedderb/bldc-hardware.

## Getting Started

The first thing required is to install KiCad from here: https://www.kicad.org/. Once downloaded, you should be able to pull from the repo and open the project. There are multiple embedded sheets from the top view that you can access.

## Sheets

#### MCU

The MCU is responsible for the control of the entire circuit. This includes getting Firmware uploaded, controlling the Motor, and receiving signals from the remote control. It is the main brain of the ESC!

#### Motor Driver

The Motor Driver takes in a PWM signal and controls the respective Power MOSFETs with those PWM signals. The driver is very important as it is used for low-voltage compatibility, transient protection, and fast switching speed.

#### Power MOSFETs

Power MOSFETs are used to drive the BLDC motor. (Angelina write something :D)
