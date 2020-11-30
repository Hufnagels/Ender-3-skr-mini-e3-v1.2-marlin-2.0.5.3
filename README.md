# Marlin 2.0.5.3 for Ender-3 with SKR Mini E3 v1.2 and Creality BLTouch 1.3

[![Build Status](https://travis-ci.org/MarlinFirmware/Marlin.svg?branch=2.0.x)](https://travis-ci.org/MarlinFirmware/Marlin)
![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)

### BigTreeTech Updated their Firmware, get it here:
https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3

## Current Target

Creality Ender-3 with SKR Mini E3 v1.2 and Creality BLTouch 3.1

## Before compile Platformio changes

[libmaple/gpio error](https://reprap.org/forum/read.php?415,874307)
## Features Enabled

- BLTouch (Bi-Linear Bed Leveling)
- Custom Status Screen (Ender-3 Default)
- Disable Boot Screens
- Disable Info Screen
- Enabled Slim Menus
- Enabled S Curve Acceleration
- Disable ARC Support (Cura does not have arc support anyway)
- Enabled Linear Advance
- Enabled Square Wave Stepping
- Enabled Hybrid Threshold for TMC2209 Stepper Drivers
- Bed Size is 230x230mm
- Enable Menu to Level Bed Corners (and Center)
- Pre-Heat for "PLA", "ABS" and "PETG"
- Fix for EEPROM saving issue

