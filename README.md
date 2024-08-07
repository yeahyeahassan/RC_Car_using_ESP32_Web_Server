# 🚗 RC Car Controller using ESP32 Web Server

Welcome to the **RC Car Controller** project! This repository contains code for controlling an RC car using an ESP32 microcontroller via WebSockets. The car can be controlled remotely through a web interface, allowing for seamless real-time communication. 🎮✨

## 🧰 Hardware Requirements
- **ESP32 Development Board** (e.g., ESP32-WROOM-32)
- **DC Motors** (2 units)
- **Motor Driver Module**
- **Power Supply** (e.g., LiPo Battery)
- **Wires & Connectors**

## 💻 Software Requirements
- **Arduino IDE** (with ESP32 board support)
- **ESPAsyncWebServer** library
- **AsyncTCP** library

## ⚙️ Pin Configuration
- **Motor 1 Pins:**
  - IN1: GPIO 2
  - IN2: GPIO 4
  - ENA: GPIO 22
- **Motor 2 Pins:**
  - IN1: GPIO 18
  - IN2: GPIO 19
  - ENB: GPIO 23

## 🚀 Getting Started
1. **Clone the repository**:
   ```bash
   git clone https://yeahyeahassan/RC_Car_using_ESP32_Web_Server
   cd rc-car-controller

2. **Install the required libraries** via Arduino IDE:
   - ESPAsyncWebServer
   - AsyncTCP

3. **Upload the code** to your ESP32 using Arduino IDE.

4. **Connect to the Wi-Fi network** created by the ESP32:
   - SSID: `rc_car`
   - Password: `987654321`

5. **Open the web interface** using the ESP32's IP address displayed on the Serial Monitor.

6. **Control your RC car** through the web interface! 🎮
---
## 📜 Code Overview

The code includes:

- **WebSocket Server**: Allows real-time communication between the car and the controller.
- **Motor Control**: Handles direction and speed of the motors based on received commands.
- **Timeout Handling**: Stops the motors if no command is received within a specified timeout period.

### ⚠️ Safety Note:
Always ensure your car is placed in a safe environment while testing to prevent any damage or injury.

## 🌟 Features

- **Real-time Control**: Instantaneous response to commands via WebSockets.
- **Customizable Speed & Direction**: Control the car's movement in all directions.
- **Automatic Timeout**: Stops the car if no commands are received to ensure safety.

![Thank You](https://img.shields.io/badge/Thank%20You!-blue?style=flat-square&logo=smile)

<!-- Graphical GIF Animation -->
<div class="gif-container" style="text-align: center; margin-bottom: 20px;">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExYzdob2I4cHdsdWhnbmtmYTBxbnk4cnl2YjZ1bGw5ZGZvMXBwdWc4bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/00n6TSoGffGTLXSMPO/giphy.gif" alt="Working on it GIF" />
</div>

