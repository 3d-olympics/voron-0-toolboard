# USB toolhead board for Voron 0.2

This board replaces the strain relief part at the back of the Voron 0.2's toolhead. It receives 24V through the a USB-C cable - a companion board/connector allows this power voltage to be injected between your RPi and the USB-C cable to this toolboard.
This is non-standard and not really advisable, so proceed at your own risk!

<img height="600" alt="image" src="https://github.com/user-attachments/assets/af8fa72f-8abc-4625-8af0-c41e5df8deec" />

## Features
* ADXL345 accelerometer, with interrupt pin connected for use as a "probe"
* TMC2209 driver for extruder motor
* STM32F042G6U6TR, 28-pin microcontroller for running Klipper
* USB-C connector with strain relief
* Connectors for heater and two thermistors
* Connector for a probe or other device e.g. LEDs
* Connectors for hotend fan and two cooling fans
* 5V buck regulator - hotend and cooling fans can separately be supplied with 5 or 24V

The project is developed in KiCad, and that's what the project files are for.

If there's any interest I'll provide some more material like gerber and BOM files.

<img height="400" alt="image" src="https://github.com/user-attachments/assets/2f802b93-a1b1-4470-acc9-c151b644af9d" /><img height="400" alt="image" src="https://github.com/user-attachments/assets/99a96dd7-1089-4bf9-8c49-00ff23f83854" />
