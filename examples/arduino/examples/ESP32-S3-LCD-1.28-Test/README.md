# ESP32-S3-LCD-1.28-Test

[简体中文](README_ZH.md)

## Function
Initializes the LCD, draws graphics, reads QMI8658 acceleration and gyroscope data, and shows the battery voltage.

## Hardware requirements
ESP32-S3-LCD-1.28 with its 1.28-inch LCD, QMI8658 sensor and battery measurement circuit.

## How to run
Open `ESP32-S3-LCD-1.28-Test.ino` in Arduino IDE, select an ESP32S3 Dev Module with 16MB Flash and OPI PSRAM, then upload it.

## Expected behavior
The display first shows drawing primitives and then continuously refreshes motion values and battery voltage.

## Common issues
The sketch keeps the display update loop running continuously. A board with unavailable PSRAM cannot allocate the frame buffer.
