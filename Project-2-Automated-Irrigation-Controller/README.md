<div align="center">

# 🌱 Automated Irrigation Controller

### IoT Industrial Training Project 2

![Platform](https://img.shields.io/badge/Platform-ESP32%20%7C%20Arduino-blue)
![Language](https://img.shields.io/badge/Language-C%2B%2B-orange)
![Automation](https://img.shields.io/badge/System-Closed%20Loop-success)
![Status](https://img.shields.io/badge/Status-Completed-success)

An automated irrigation system that monitors soil moisture and controls a water pump using relay-based actuator logic.

</div>

---

# 📖 Overview

The **Automated Irrigation Controller** is a closed-loop IoT system designed to automate irrigation based on real-time soil moisture levels.

The microcontroller continuously reads analog values from a soil moisture sensor, processes the readings using ADC, compares them against a predefined threshold, and automatically switches a relay module to control a water pump.

This project demonstrates embedded automation and real-time decision making.

---

# 🎯 Objectives

- Read analog sensor values
- Learn ADC
- Implement threshold logic
- Control relay modules
- Automate irrigation
- Build a closed-loop embedded system

---

# ✨ Features

- 🌱 Soil Moisture Monitoring
- 📈 Analog Data Processing
- ⚡ ADC Implementation
- 🔄 Automatic Irrigation
- 🔌 Relay Control
- 🚰 Water Pump Automation
- 🤖 Closed-Loop Decision Making

---

# 🛠 Hardware Components

| Component | Quantity |
|-----------|----------|
| ESP32 / Arduino | 1 |
| Soil Moisture Sensor | 1 |
| 5V Relay Module | 1 |
| Water Pump (or Simulation) | 1 |
| Breadboard | 1 |
| Jumper Wires | As Required |
| USB Cable | 1 |

---

# 💻 Software Requirements

- Arduino IDE
- ESP32 Board Package
- Analog Read Functions
- Digital Output Functions

---

# 🔌 System Architecture

```
 Soil Moisture Sensor
          │
          ▼
   ESP32 / Arduino
          │
   Threshold Logic
          │
          ▼
     Relay Module
          │
          ▼
      Water Pump
```

---

# ⚙ Working Principle

1. Read analog value from the soil moisture sensor.
2. Convert voltage into a digital value using ADC.
3. Compare the value against a predefined threshold.
4. If soil moisture is below the threshold:
   - Turn ON relay.
   - Activate water pump.
5. If sufficient moisture is detected:
   - Turn OFF relay.
   - Stop the pump.
6. Repeat continuously.

---

# 📂 Folder Structure

```
Project-2-Automated-Irrigation-Controller
│
├── Source_Code/
├── Circuit_Diagram/
├── Images/
└── README.md
```

---

# 📚 Concepts Covered

- Analog-to-Digital Conversion (ADC)
- Embedded Automation
- Relay Control
- Threshold Logic
- Sensor Calibration
- Closed-Loop Systems
- Embedded Decision Making

---

# 🚀 Future Improvements

- Wi-Fi Monitoring
- Mobile App Control
- MQTT Integration
- Cloud Dashboard
- Weather Forecast Integration
- Smart Scheduling
- AI-Based Irrigation Prediction

---

# 🎓 Learning Outcomes

- Embedded Control Systems
- Analog Signal Processing
- Actuator Control
- Relay Interfacing
- Real-Time Automation
- IoT System Design

---

<div align="center">

⭐ Industrial IoT Training Project

</div>
