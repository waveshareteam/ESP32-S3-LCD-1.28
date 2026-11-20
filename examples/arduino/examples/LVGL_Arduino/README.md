# LVGL_Arduino

[简体中文](README_ZH.md)

## Function
Initializes LVGL and TFT_eSPI, displays an image from the sketch data and periodically switches the image.

## Hardware requirements
ESP32-S3-LCD-1.28 with its GC9A01 LCD and the bundled LVGL and TFT_eSPI libraries.

## How to run
Open `LVGL_Arduino.ino`, select an ESP32S3 Dev Module with 16MB Flash and OPI PSRAM, then upload it.

## Expected behavior
The LCD shows the bundled image and changes the displayed image on the timer callback.

## Common issues
The sketch uses LVGL 8 APIs and the bundled library configuration. Do not replace the bundled LVGL major version.
