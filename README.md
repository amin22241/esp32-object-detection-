# ESP32-CAM Object Detection System

## Overview
This project uses the **ESP32-CAM** module to stream live video over a local network and lays the foundation for object detection. With its low cost, onboard camera, and wireless capabilities, this setup is perfect for home surveillance, AI projects, smart doorbells, and more.

## Features
- Live video streaming via local IP
- Real-time object detection capability (basic or cloud-integrated)
- Compact and low-power design
- Wireless communication via Wi-Fi
- Potential for cloud services, face recognition, and more

## Hardware Requirements
- ESP32-CAM module (AI-Thinker or compatible)
- FTDI programmer (USB to TTL converter)
- Micro USB cable
- 5V power supply (≥1A recommended)
- Jumper wires
- Breadboard (optional for easier wiring)

## Software Requirements
- [Arduino IDE](https://www.arduino.cc/en/software)
- ESP32 board support for Arduino
- Required libraries:
  - `esp32`
  - `WiFi`
  - `esp_camera`
  - `FS.h`, `SD.h` (for optional SD card support)

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/amin22241/esp32-object-detection-/tree/main
