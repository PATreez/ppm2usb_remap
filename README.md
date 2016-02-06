# ppm2usb_remap
This is based on "PPM2USB, a AVR-based PPM to USB-Joystick Converter using V-USB" by Thomas Pfeifer

This code is a slightly modified version of "AVR-based PPM to USB-Joystick Converter using V-USB" which is located at:
https://github.com/thomaspfeifer/PPM2USB/tree/feature/USBASP

The modifications made were:

- Modified the usbHidReportDescriptor to emulate a Joystick which has X-axis, Y-axis, Z-axis, X-rotation and Buttons 1-4
- Remap/reorder the PPM signal channel numbers
