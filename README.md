# cmake toolchain for AVR projects

This project is forked fom [mkleemann repo](https://github.com/mkleemann/cmake-avr).

The initial motivation of this fork is the inability to make work avrdude with pickit4 in mac and adapt the cmake project to work with [ipecmd](https://microchip.my.site.com/s/article/Automate-MPLAB-programming-process-using-command-lineIPECMD) flashing tool.

## The example provided was tested in:

The toolchain was created and tested within the following environment:

macOS 
* macOS 14.0 Beta
* avr toolchain: Homebrew AVR GCC 9.4.0
* cmake version 3.27.5
* mplabx version v6.15
* java 20.0.2
