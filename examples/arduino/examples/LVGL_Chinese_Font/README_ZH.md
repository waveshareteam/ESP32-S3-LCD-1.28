# LVGL_Chinese_Font

[English](README.md)

## 功能
使用 LVGL 内置 SimSun 字体显示彩色中文文字，并读取 CST816S 触摸控制器。

## 硬件需求
ESP32-S3-LCD-1.28、板载 GC9A01 LCD 和 CST816S 触摸控制器。

## 怎么运行
打开 `LVGL_Chinese_Font.ino`，选择 16MB Flash 和 OPI PSRAM 的 ESP32S3 Dev Module，然后上传。

## 预期现象
LCD 居中显示彩色中文文字，CST816S 触摸输入正常注册。

## 常见问题
示例使用开发板 I2C 引脚上的 CST816S 控制器，并依赖仓库 LVGL 配置中启用的 SimSun 字体。
