# ESP32-S3-LCD-1.28-Test

[English](README.md)

## 功能
初始化 LCD，绘制图形，读取 QMI8658 加速度和陀螺仪数据，并显示电池电压。

## 硬件需求
ESP32-S3-LCD-1.28、板载 1.28 英寸 LCD、QMI8658 传感器和电池测量电路。

## 怎么运行
在 Arduino IDE 打开 `ESP32-S3-LCD-1.28-Test.ino`，选择 16MB Flash 和 OPI PSRAM 的 ESP32S3 Dev Module，然后上传。

## 预期现象
屏幕先显示图形绘制效果，然后持续刷新运动数据和电池电压。

## 常见问题
示例会持续运行显示刷新循环。没有可用 PSRAM 时无法申请帧缓冲区。
