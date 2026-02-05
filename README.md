# arduinoFlasher Framework
This is a web-based firmware recovery tool for Arduino Pro Micro (ATmega32U4) based button boxes. It allows customers to re-flash their devices directly from a browser without installing the Arduino IDE or manually resetting the board.

# How it Works
This tool uses the AVRgirl-arduino library.

Auto-Reset: It triggers a software reset by opening a serial connection at 1200 baud, which kicks the Pro Micro into bootloader mode automatically.

Web Serial API: It communicates with the USB hardware directly via Chrome or Edge browsers.
