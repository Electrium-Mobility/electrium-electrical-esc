# Electrium ESC V1.0

---

This is the initial version of the Electronic Speed Controller. Heavy reference was from the VESC 4.11 model from here: https://github.com/vedderb/bldc-hardware.

## Sheets

---

#### MCU

The MCU is responsible for the control of the entire circuit. This includes getting Firmware uploaded, controlling the Motor controlling, and receiving signals from the remote control.

#### Motor Driver

The Motor Driver takes in a PWM signal and controls the respective Power MOSFETs with those PWM signals. The driver is very important as it is used for low-voltage compatibility, transient protection, and fast switching speed.

#### Power MOSFETs

Power MOSFETs are used to drive the BLDC motor. (Angelina write something :D)
