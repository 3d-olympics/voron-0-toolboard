# USB toolhead board for Voron 0.2

This board replaces the strain relief part at the back of the Voron 0.2's toolhead. It receives 24V through the a USB-C cable - a companion board/connector allows this power voltage to be injected between your RPi and the USB-C cable to this toolboard.
This is non-standard and not really advisable, so proceed at your own risk!

<img width="1471" height="1512" alt="image" src="https://github.com/user-attachments/assets/6a8aaf9d-0924-4c45-af7a-cd847a6806da" /><img width="1608" height="1515" alt="image" src="https://github.com/user-attachments/assets/d474d93c-41c8-4ac4-b39a-34edda6c5cec" />

## Features
* USB-C connector with strain relief
* ADXL345 accelerometer
* Standard connections for extruder motor, heater and two thermistors
* Connector for a probe or other device e.g. LEDs
* 5V buck regulator - fans can individually be supplied with 5 or 24V

The project is developed in KiCad, and that's what the project files are for.

If there's any interest I'll provide some more material like gerber and BOM files.

This version, rev3, will be tested shortly. Rev2 worked well.
