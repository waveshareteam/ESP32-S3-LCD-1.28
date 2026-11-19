# LVGL_Chinese_Font

[简体中文](README_ZH.md)

## Function
Displays recolored Chinese text with the LVGL built-in SimSun font and reads the CST816S touch controller.

## Hardware requirements
ESP32-S3-LCD-1.28 with its GC9A01 LCD and CST816S touch controller.

## How to run
Open `LVGL_Chinese_Font.ino`, select an ESP32S3 Dev Module with 16MB Flash and OPI PSRAM, then upload it.

## Expected behavior
Colored Chinese text appears centered on the LCD and touch input is registered through CST816S.

## Common issues
The sketch expects the CST816S controller on the board I2C pins and the SimSun font enabled in the bundled LVGL configuration.
