# Smart Guitar Capo 

### **[CURRENTLY IN BEGINNING STAGES]**

A hybrid hardware-software project that combines a 3D-printed guitar capo with embedded IoT hardware and web-based audio analysis to help guitar users see which note they are currently playing via electronic status display. In other words, its an intelligent guitar capo equipped with embedded sensors and Bluetooth connectivity. Smart Capo detects real-time fret position, monitors string tension and tuning accuracy, and syncs seamlessly with a mobile companion app for auto-transposition, tabs, and performance analytics.

---

## Table of Contents

- [Key Features](#-key-features)
- [System Architecture](#-system-architecture)
- [Hardware & Component List](#-hardware--component-list)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Firmware Setup](#firmware-setup)
  - [Mobile App Setup](#mobile-app-setup)
- [Usage & Calibration](#-usage--calibration)
- [Repository Structure](#-repository-structure)
- [Contributing](#-contributing)
- [License](#-license)

---

## Key Features

- **Real-Time Fret Detection:** Automatically detects which fret the capo is clamped onto.
- **Auto-Transposition:** Instantly transposes chord charts and tabs in the app based on capo placement.
- **Tension & Pressure Monitoring:** Prevents sharp notes and neck damage by alerting you if the clamp is too tight or loose.
- **Integrated Micro-Tuner:** Provides quick tuning verification directly from the capo's LED display.
- **Low Energy Bluetooth (BLE):** Long battery life with fast, seamless pairing to iOS and Android devices.

---

## System Architecture
---

## 🛠️ Hardware & Component List

| Component | Description | Recommended Part |
| :--- | :--- | :--- |
| **Microcontroller** | BLE-enabled, low-power MCU | ESP32-C3 / ESP32-S3 |
| **Position Sensor** | Contact/fret sensing module | Force Sensitive Resistor (FSR) / Capacitive Touch |
| **Pressure Sensor** | Clamp force measurement | Mini strain gauge / FSR |
| **Display** | On-capo feedback | 0.96" OLED or Multi-color LED bar |
| **Power** | Rechargeable LiPo battery | 3.7V 150mAh + TP4056 Charger |

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

* **Firmware development:** [PlatformIO](https://platformio.org/) or [Arduino IDE](https://www.arduino.cc/en/software)
* **Mobile app development:** [Flutter](https://flutter.dev/) or [React Native](https://reactnative.dev/)
* **Hardware toolchain:** Serial drivers (CP210x / CH340) for your microcontroller

---

### Firmware Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/smart-guitar-capo.git](https://github.com/dgarciaperales/smart-capo.git)
   cd smart-capo/firmware
