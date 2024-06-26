# PixelClick

PixelClick is a tiny (33x33mm) LED matrix (6x6) with 4 buttons and ESP32S3 N16R8. It can be programmed with USB-C and any computer.

## Possible use cases
- **Status light**. It can be used to reflect your current status. Are you in a meeting or working in a flow, it can reflect it with the click of a button. Pair 2 PixelClick and one can be used as a controller and the second as a notification light outside of the office room.
- **Pomodoro timer** with fixed working time and interval time. It can change the color or play animations based on the current mode.
- **Simple game**. You can make a simple game to test your reaction.
- **ESPHOME** light and a button, can be a fancy doorbell or any other smart button.

![Render of the board](./pcb/render.png)

## List of features
- 36 addressable LEDs sk6805
- 4 buttons on the front side (one of the buttons is IO0)
- 2 programmable LEDs for blick the LED programs (hello world) or some debug
- 1 reset button on the back
- ESP32S3 R8 as the main brain, right in the center
- 16MB flash
- Chip antenna for WiFi and BT
- ESD protection for USB
- USB-C for data and power

## Programming

This board is compatible with C++ (Arduino) and Rust

Code examples will be provided soon.

## PCB

PCB KiCAD 8 files are available for [Patreon Partners](https://www.patreon.com/brushknight_maker).

### PCB layout

![PCB layout](./pcb/pcb_layout.png)

### PCB schematics

![PCB schematics](./pcb/schematics.png)
For better quality of the PCB schematics, check this [PDF](./pcb/schematics.pdf)

### PCB BOM (components) file
[ibom.html](./pcb/ibom.html)
