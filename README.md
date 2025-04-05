# 🌱 PLC Greenhouse Automation System

This project presents a fully functional **greenhouse automation system** developed using a **Programmable Logic Controller (PLC)**. The system controls environmental parameters such as **temperature**, **humidity**, and **soil moisture**, automating the activation of **irrigation**, **ventilation**, and **heating** systems.

It simulates a real-world industrial application, demonstrating the use of **Ladder Logic** and **Structured Text** in creating reliable, scalable, and maintainable control systems.

---

## 🎯 Project Objectives

- Design a smart greenhouse system using PLC programming.
- Monitor and control multiple environmental variables.
- Automate actuation of watering, fans, and heating based on sensor inputs.
- Implement modular, reusable ladder logic routines.
- Integrate safety and fail-safe conditions.

---

## 🧱 System Overview

| Subsystem         | Description |
|------------------|-------------|
| **Sensors**       | Readings from temperature, humidity, and soil moisture sensors. |
| **Actuators**     | Relay-controlled water pumps, ventilation fans, and heating elements. |
| **HMI (optional)**| Touch panel or PC interface to adjust thresholds and monitor system state. |
| **PLC Logic**     | Ladder Logic and Structured Text programs control the system behavior. |

---

## 🛠️ Platform & Tools

- **PLC Model**: Siemens S7-1200 (or compatible)  
- **Programming Software**: TIA Portal  
- **Programming Languages**: 
  - **Ladder Logic (LD)** for core control flow  
  - **Structured Text (ST)** for data processing and logic abstraction
  - **Grafcet (GF)** 
- **Simulation**: PLCSIM / Factory I/O (optional)

---

## ⚙️ Features


- 🔁 **Manual / Automatic Modes**  
  The system can switch between manual control (for testing or maintenance) and full automatic operation.

- 🏭 **Parallel Greenhouse Management**  
  Controls and monitors two independent greenhouse units simultaneously, each with its own actuators and environment control.

- 🚚 **Integrated Transport System**  
  Each greenhouse has a dedicated conveyor or AGV-based transport system for seed handling, plant movement, or packaging flow.

- 🌱 **Plant Growth Cycle Management**  
  Tracks each crop’s growth stage using timers and conditions, adjusting environmental variables as needed for optimal development.

- 🌾 **Seed Selection with Variable Growth Timers**  
  Operators can choose from different seed types, each with unique growth times and conditions, managed automatically by the system.

- 📦 **Automated Packaging and Storage**  
  Once crops reach full growth, the system triggers an embasado (packaging) and transports the harvest to a designated storage area.

- 🚫 **AGV Collision Handling**  
  Detects and prevents collisions between Automated Guided Vehicles using sensors and safety logic routines.

---

## 🧪 Testing & Validation

- **Unit tests** with PLCSIM for each control block.
- Simulated input values from virtual sensors.
- **Factory I/O integration** (optional) for full digital twin testing.
- Manual override tests via HMI panel or switches.

---
