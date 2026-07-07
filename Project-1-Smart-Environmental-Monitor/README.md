<div align="center">

# 🌡️ Smart Environmental Monitor

### IoT Industrial Training Project 1

![Platform](https://img.shields.io/badge/Platform-ESP32%20%7C%20Arduino-blue)
![Language](https://img.shields.io/badge/Language-C%2B%2B-orange)
![Domain](https://img.shields.io/badge/Domain-IoT-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

Monitor environmental conditions using a DHT sensor and display real-time temperature and humidity data.

</div>

---

# 📖 Overview

The **Smart Environmental Monitor** is an introductory IoT project focused on developing the fundamental skills required for embedded systems programming.

The system reads **temperature** and **humidity** from a DHT11/DHT22 sensor using an ESP32 or Arduino board and continuously displays the measurements through the Serial Monitor or an optional I2C LCD.

This project demonstrates how physical environmental data can be acquired, processed, and displayed using a microcontroller.

---

# 🎯 Objectives

- Interface a DHT11/DHT22 sensor
- Read environmental data
- Configure GPIO pins
- Display sensor readings
- Learn Serial Communication
- Understand embedded programming basics

---

# ✨ Features

- 🌡️ Real-Time Temperature Monitoring
- 💧 Humidity Measurement
- 📟 Serial Monitor Output
- 🖥 Optional I2C LCD Display
- 🔄 Continuous Sensor Sampling
- ⚡ Lightweight Embedded Firmware

---

# 🛠 Hardware Components

| Component | Quantity |
|-----------|----------|
| ESP32 / Arduino | 1 |
| DHT11/DHT22 Sensor | 1 |
| Breadboard | 1 |
| Jumper Wires | As Required |
| USB Cable | 1 |
| I2C LCD (Optional) | 1 |

---

# 💻 Software Requirements

- Arduino IDE
- ESP32 Board Package (if using ESP32)
- DHT Sensor Library
- Wire Library
- Serial Monitor

---

# 🔌 Circuit Overview

```
      DHT Sensor
      ┌────────┐
 VCC──┤ VCC    │
 GND──┤ GND    │
GPIO──┤ DATA   │
      └────────┘
            │
            ▼
       ESP32 / Arduino
```

---

# ⚙ Working Principle

1. Initialize the microcontroller.
2. Configure the sensor GPIO pin.
3. Initialize the DHT library.
4. Read temperature and humidity every 2 seconds.
5. Display readings on the Serial Monitor or LCD.
6. Repeat continuously.

---

# 📂 Folder Structure

```
Project-1-Smart-Environmental-Monitor
│
├── Source_Code/
├── Circuit_Diagram/
├── Images/
└── README.md
```

---

# 📚 Concepts Covered

- Embedded Systems
- GPIO Configuration
- Sensor Interfacing
- Digital Communication
- Serial Debugging
- I2C Communication
- Real-Time Data Acquisition

---

# 📸 Demonstration

Add your project images here.

```
Images/
│
├── setup.jpg
├── wiring.png
├── serial-monitor.png
└── lcd-output.jpg
```

---

# 🚀 Future Improvements

- OLED Display
- Wi-Fi Connectivity
- MQTT Integration
- Cloud Monitoring
- Blynk Dashboard
- Mobile Notifications
- Data Logging

---

# 🎓 Learning Outcomes

- Microcontroller Programming
- Sensor Integration
- Hardware Debugging
- Serial Communication
- Embedded Firmware Development

---

<div align="center">

⭐ Industrial IoT Training Project

</div>
