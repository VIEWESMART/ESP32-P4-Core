# ESP32-P4-Core
[English](https://github.com/VIEWESMART/ESP32-P4-Core/edit/main/README.md) | [中文](https://github.com/VIEWESMART/ESP32-P4-Core/blob/main/README_CN.md)

<img width="1200" height="804" alt="image" src="https://github.com/user-attachments/assets/58394e92-7423-4337-9d05-b1d79f2f30bd" />

## 1 简介
ESP32-P4-Core是Viewe基于ESP32-P4芯片设计的高性能双核RISC-V模块。它采用ESP32-C6FH4来扩展WIFI6功能。支持多种人机交互接口，包括MIPI-CSI（集成图像信号处理器ISP）和MIPI-DSI接口。此外，还支持SPI、I2S、I2C、LED PWM、MCPWM、RMT、ADC、UART和TWAI™等常见外设。同时支持USB OTG 2.0 HS、以太网和SDIO Host 3.0高速连接，其外设针对低功耗应用进行了优化。该芯片集成了数字签名外设和专用密钥管理单元，以确保其安全性。ESP32-P4-Core专为高性能和高安全性应用而设计，支持超大片上内存，并具备强大的图像和语音处理能力。它充分满足了嵌入式应用在人机界面支持、边缘计算能力和IO连接特性方面的更高要求。

## 2 功能特点
### 2.1 中央处理器（CPU）
• 适用于高性能（HP）系统的32位RISC-V双核处理器，最高频率400 MHz

• 适用于低功耗（LP）系统的32位RISC-V单核处理器，最高频率40 MHz

• 配备ESP32-C6 WIFI/蓝牙协处理器，通过SDIO扩展WIFI 6和蓝牙5等功能

### 2.2 存储器
• 128 KB高性能（HP）只读存储器（ROM）

• 16 KB低功耗（LP）只读存储器（ROM）

• 768 KB高性能（HP）二级存储器（L2MEM）

• 32 KB低功耗（LP）静态随机存取存储器（SRAM）

• 8 KB系统暂存存储器（SPM）

• 内部堆叠封装32 MB伪静态随机存取存储器（PSRAM），通过QSPI接口连接16 MB Nor闪存。

### 2.3 应用领域
ESP32-P4功耗低，是以下领域物联网设备的理想选择：

• 智能家居

• 工业自动化

• 医疗健康

• 消费电子

• 智慧农业

• 零售自助终端（POS机、自动售货机）

• 服务机器人

• 多媒体播放器

• 视频流摄像头

• 高速USB主机和设备

• 智能语音交互终端

• 边缘视觉人工智能处理器

• 人机界面控制面板

## 3 产品尺寸
<img width="1299" height="765" alt="image" src="https://github.com/user-attachments/assets/0f49fdea-6442-4455-b18b-99c995e341b3" />

## 4 引脚定义
![d68e760e7869297da0741a895e2d4840](https://github.com/user-attachments/assets/a7cf9b36-b82a-4bbd-9874-a7b4af29ea3b)

<img width="1117" height="487" alt="image" src="https://github.com/user-attachments/assets/4a2175fc-0bc2-45c1-8300-ab0f980e00dd" />

## 5 GPIO 描述说明
<img width="940" height="1338" alt="image" src="https://github.com/user-attachments/assets/4b29cc28-00f6-4d7c-8b21-4d8aaa5f8e5b" />
<img width="940" height="1432" alt="image" src="https://github.com/user-attachments/assets/4772b718-1310-45d4-8494-5d4ee0185a92" />
<img width="940" height="1436" alt="image" src="https://github.com/user-attachments/assets/c5a67759-1c23-4486-9a15-99d76ce6f72e" />
<img width="940" height="878" alt="image" src="https://github.com/user-attachments/assets/c90f2065-ccb8-4b57-8d7e-65750ed2619b" />

## 6 外接天线图纸
<img width="1279" height="1655" alt="image" src="https://github.com/user-attachments/assets/b7e0a88d-2f2a-4b75-91b1-517c92fd702d" />

## 7 相关资料
### 7.1 原理图
[ESP32-P4-Core Schematic Diagram](https://github.com/VIEWESMART/ESP32-P4-Core/blob/main/Schematic/SCH_ESP32-P4-Core_2025-11-24.pdf)
### 7.2 3D图纸
[ESP32-P4-Core 3D Drawing]()
### 7.3 PCB 封装图纸
[ESP32-P4-Core Footprint Drawing]()
### 7.4 数据手册
[ESP32-P4 Datasheet(中文)](https://github.com/VIEWESMART/ESP32-P4-Core/blob/main/Datasheet/esp32-p4-chip-revision-v1.3_datasheet_cn.pdf)

[ESP32-P4 Datasheet(英文)](https://github.com/VIEWESMART/ESP32-P4-Core/blob/main/Datasheet/esp32-p4-chip-revision-v1.3_datasheet_en.pdf)

[ESP32-P4 技术参考手册(中文)](https://github.com/VIEWESMART/ESP32-P4-Core/blob/main/Datasheet/Esp32-p4_technical_reference_manual_cn.pdf)

[ESP32-P4 技术参考手册(英文)](https://github.com/VIEWESMART/ESP32-P4-Core/blob/main/Datasheet/Esp32-p4_technical_reference_manual_en.pdf)

[FR 天线数据手册](https://github.com/VIEWESMART/ESP32-P4-Core/blob/main/Datasheet/734120110_sd.pdf)
### 7.5 设计参考
[ESP32-P4-PI-VIEWE原理图](https://github.com/VIEWESMART/ESP32-P4-Core/blob/main/Schematic/SCH_ESP32-ESP32-P4-Pi-VIEWE-V1.1_2025-10-23.pdf)
