# Game of Life on the Raspberry Pi Pico with OLED screen
MicroPython script to run Game of Life on the Raspberry Pi Pico with 128 px x 64 px OLED screen.

![Project image](img/project_img.jpg?raw=true)

## Detailed description
Schematic of the connections can be found in the connections.pdf file. OLED screen with SH1106 driver was used. It will not work if screen has different driver chip. Documentation on how to use MicroPython on the Raspberry Pi Pico can be found [here](https://datasheets.raspberrypi.org/pico/raspberry-pi-pico-python-sdk.pdf).

## Dependencies
You need one library to run this script:

[SH1106](https://github.com/robert-hh/SH1106)

sh1106.py file should be copied into the /lib directory crated in the main directory of the microcontroller.
