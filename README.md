<div align="center">

# 🌐 IoT Industrial Training Projects
### Smart Environmental Monitor & Automated Irrigation Controller

[![Platform](https://img.shields.io/badge/Platform-ESP32%20%7C%20Arduino-blue.svg)]()
[![Language](https://img.shields.io/badge/Language-C%2B%2B-orange.svg)]()
[![Domain](https://img.shields.io/badge/Domain-IoT-green.svg)]()
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

**Industrial IoT Training Projects developed during DecodeLabs Industrial Training Program (Batch 2026).**

*Building intelligent embedded systems through real-world sensor interfacing, actuator control, and hardware-software integration.*

</div>

---

# 📖 Overview

This repository contains two Industrial Internet of Things (IoT) projects focused on developing practical embedded systems using microcontrollers, environmental sensors, and actuator control.

The projects emphasize fundamental IoT concepts including:

- Embedded Programming
- GPIO Configuration
- Digital Sensor Interfacing
- Analog-to-Digital Conversion (ADC)
- Serial Communication
- Threshold-based Decision Making
- Relay Control
- Closed-Loop Automation

These projects demonstrate how embedded systems collect environmental data, process it, and make autonomous decisions without human intervention.

---

# 📂 Repository Structure

```
IoT-Industrial-Projects/
│
├── Project-1-Smart-Environmental-Monitor/
│   ├── Source Code
│   ├── Circuit Diagram
│   ├── Images
│   └── README.md (optional)
│
├── Project-2-Automated-Irrigation-Controller/
│   ├── Source Code
│   ├── Circuit Diagram
│   ├── Images
│   └── README.md (optional)
│
└── README.md
```

---

# 🚀 Project 1 – Smart Environmental Monitor

## 🎯 Objective

Develop an embedded system capable of monitoring environmental conditions by reading temperature and humidity data from a digital sensor and displaying the information in real time.

---

## ✨ Features

- Reads Temperature
- Reads Humidity
- Digital Sensor Interfacing
- Real-Time Data Monitoring
- Serial Monitor Output
- I2C LCD Support (Optional)
- Continuous Sensor Sampling
- Reliable Embedded Firmware

---

## 🛠 Hardware Components

- ESP32 / Arduino Development Board
- DHT11 or DHT22 Sensor
- Jumper Wires
- Breadboard
- I2C LCD (Optional)
- USB Cable

---

## 💻 Software Used

- Arduino IDE
- ESP32 Board Package
- DHT Sensor Library
- Wire Library
- Serial Monitor

---

## ⚙ Working Principle

1. Initialize the microcontroller.
2. Configure GPIO pins.
3. Initialize the DHT sensor.
4. Read temperature and humidity every 2 seconds.
5. Display values on Serial Monitor or LCD.
6. Repeat continuously inside the execution loop.

---

## 📚 Concepts Learned

- Embedded Programming
- GPIO Configuration
- Sensor Communication
- Digital Protocols
- Data Acquisition
- Serial Debugging
- I2C Communication

---

# 🌱 Project 2 – Automated Irrigation Controller

## 🎯 Objective

Design a closed-loop automated irrigation system that continuously monitors soil moisture and automatically controls a water pump using relay-based actuator logic.

---

## ✨ Features

- Soil Moisture Monitoring
- Analog Sensor Reading
- ADC Implementation
- Automatic Water Pump Control
- Relay Module Interface
- Threshold-Based Decision Logic
- Closed-Loop Automation
- Fully Autonomous Operation

---

## 🛠 Hardware Components

- ESP32 / Arduino
- Soil Moisture Sensor
- 5V Relay Module
- Water Pump (or Simulation)
- Breadboard
- Jumper Wires
- USB Cable

---

## 💻 Software Used

- Arduino IDE
- ESP32 Board Package
- Analog Read Functions
- Digital Output Control

---

## ⚙ Working Principle

1. Read analog value from the soil moisture sensor.
2. Convert analog voltage using ADC.
3. Compare the reading with a predefined threshold.
4. If soil is dry:
   - Turn ON relay.
   - Activate water pump.
5. If soil moisture becomes sufficient:
   - Turn OFF relay.
   - Stop the pump.
6. Repeat continuously.

---

## 📚 Concepts Learned

- Analog-to-Digital Conversion (ADC)
- Threshold Logic
- Relay Control
- Digital Outputs
- Embedded Decision Making
- Closed-Loop Control Systems
- Physical Computing

---

# 🔄 System Workflow

```text
             Environmental Data
                     │
                     ▼
              Sensor Acquisition
                     │
                     ▼
        Microcontroller Processing
                     │
        ┌────────────┴────────────┐
        │                         │
        ▼                         ▼
 Project 1                 Project 2
Display Data          Compare Threshold
                              │
                              ▼
                      Relay Control
                              │
                              ▼
                        Water Pump
```

---

# 🧠 Skills Demonstrated

- Embedded Systems Programming
- Internet of Things (IoT)
- ESP32 Development
- Arduino Programming
- GPIO Configuration
- Sensor Interfacing
- ADC
- Relay Control
- Real-Time Monitoring
- Automation Logic
- Firmware Development
- Hardware Debugging
- Serial Communication
- I2C Communication
- Embedded C++

---

# 📈 Future Improvements

- Wi-Fi Connectivity
- MQTT Integration
- Blynk Dashboard
- Cloud Data Logging
- Mobile Application
- OLED Display
- Multiple Sensor Support
- Weather API Integration
- AI-based Irrigation Prediction
- Remote Monitoring
- OTA Firmware Updates

---

# 🏆 Learning Outcomes

Through these projects, the following embedded engineering concepts were successfully implemented:

- Hardware-Software Integration
- Environmental Data Acquisition
- Digital Sensor Communication
- Analog Signal Processing
- Embedded Control Systems
- Autonomous Decision Making
- Real-Time Monitoring
- Industrial IoT Fundamentals

---

# 📋 Technologies

| Category | Technology |
|----------|------------|
| Programming | C++ |
| IDE | Arduino IDE |
| Platform | ESP32 / Arduino |
| Communication | Serial, I2C |
| Sensors | DHT11/DHT22, Soil Moisture |
| Actuator | Relay Module |
| Domain | Embedded Systems & IoT |

---

# 🤝 Acknowledgements

This work was completed as part of the **Industrial IoT Training Program (Batch 2026)**, where the primary focus was developing practical embedded systems through hands-on hardware implementation, sensor interfacing, actuator control, and firmware development.

---

<div align="center">

## ⭐ If you found this repository useful, consider giving it a star!

**Made with ❤️ using Embedded Systems & IoT**

</div>
