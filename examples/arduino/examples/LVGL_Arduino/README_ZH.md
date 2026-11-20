# LVGL_Arduino

[English](README.md)

## 功能
初始化 LVGL 和 TFT_eSPI，显示示例数据中的图片，并按定时器切换图片。

## 硬件需求
ESP32-S3-LCD-1.28、板载 GC9A01 LCD 以及仓库提供的 LVGL 和 TFT_eSPI 库。

## 怎么运行
打开 `LVGL_Arduino.ino`，选择 16MB Flash 和 OPI PSRAM 的 ESP32S3 Dev Module，然后上传。

## 预期现象
LCD 显示示例图片，定时器回调触发后切换显示图片。

## 常见问题
示例使用 LVGL 8 API 和仓库中的库配置，不要替换 LVGL 大版本。
