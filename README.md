# push-to
A sensor based Universal and inexpensive Push-to system for manual telescopes

This system utilizes:
1 Raspberry Pi Zero W w/header pins
1 Arduino Nano 
1 MPU-6050 6 Axis Gyro/Accelerometer
1 1.3inch OLED Display HAT 128x64 Pixels SPI/I2C Interface w/Embedded Controller
1 Powerbank (runtime will vary with capacity) - used to power the whole system
Several 3d printed parts (STL files will be included in repository and Thingiverse)

The purpose of this project is to provide digital setting circles for my Apertua AD8 Dobsonian Telescope.
The idea is to be able to have help finding celestial targets in light polluted skies where fewer stars are visible.

The joystick on the display allows the selection of several targets, up/down changes from planets to stars and deep-sky, and right/left scrolls thorugh the targets.
The targets are coded in for now and everything is written in python.

Scope must be perfectly level and pinting tru north when the system is initialized to get good readings.
Accuracy is 1 degree or better.
